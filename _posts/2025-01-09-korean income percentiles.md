---
layout: single
title: "Income and Tax percentiles in 2022"
cagegories: 일상
tag: [소득, 세금, 한국, 차트]
author_profile: false
---
<head>
  <link rel="stylesheet" href="assets\css\2025-01-09-korean income percentiles">
</head>
<p>2025-01-10 작성</p>
<p><b>HTML을 이용해 차트그리는 방법을 연습한 결과물</b></p>

<div>
  <canvas id="myChart"></canvas>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script src="https://cdn.jsdelivr.net/npm/chartjs-plugin-datalabels@2.0.0"></script>

<script>
  const ctx = document.getElementById('myChart');

  new Chart(ctx, {
    type: 'line',
    data: {
      labels: ['100%내', '99%내', '98%내', '97%내', '96%내', '95%내', '94%내', '93%내', '92%내', '91%내', '90%내', '89%내', '88%내', '87%내', '86%내', '85%내', '84%내', '83%내', '82%내', '81%내', '80%내', '79%내', '78%내', '77%내', '76%내', '75%내', '74%내', '73%내', '72%내', '71%내', '70%내', '69%내', '68%내', '67%내', '66%내', '65%내', '64%내', '63%내', '62%내', '61%내', '60%내', '59%내', '58%내', '57%내', '56%내', '55%내', '54%내', '53%내', '52%내', '51%내', '50%내', '49%내', '48%내', '47%내', '46%내', '45%내', '44%내', '43%내', '42%내', '41%내', '40%내', '39%내', '38%내', '37%내', '36%내', '35%내', '34%내', '33%내', '32%내', '31%내', '30%내', '29%내', '28%내', '27%내', '26%내', '25%내', '24%내', '23%내', '22%내', '21%내', '20%내', '19%내', '18%내', '17%내', '16%내', '15%내', '14%내', '13%내', '12%내', '11%내', '10%내', '9%내', '8%내', '7%내', '6%내', '5%내', '4%내', '3%내', '2%내', ' 1% 내'],
      datasets: [{
        label: '인당소득',
        data: [21, 87, 155, 216, 283, 356, 420, 493, 569, 633, 710, 778, 855, 935, 1011, 1095, 1175, 1232, 1315, 1399, 1470, 1549, 1629, 1709, 1785, 1854, 1930, 2006, 2078, 2149, 2210, 2271, 2300, 2330, 2376, 2402, 2438, 2487, 2530, 2578, 2628, 2676, 2728, 2779, 2834, 2887, 2942, 2995, 3045, 3105, 3165, 3225, 3285, 3349, 3413, 3479, 3546, 3608, 3675, 3751, 3830, 3909, 3992, 4076, 4165, 4251, 4348, 4448, 4550, 4657, 4766, 4875, 4996, 5121, 5254, 5392, 5536, 5684, 5840, 5998, 6169, 6360, 6562, 6773, 6995, 7227, 7477, 7742, 8024, 8327, 8659, 9035, 9462, 9960, 10600, 11407, 12408, 13889, 16532, 19062],
        borderColor: 'rgb(0, 0, 255)',
        pointRadius: 0,
        borderWidth: 1,
        yAxisID: 'y1'
        }, {
        label: '공공기관 직원 평균보수',
        data: [null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,6875.9,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null],
        borderColor: 'rgb(0, 255, 0)',
        pointRadius: 5,
        borderWidth: 1,
        yAxisID: 'y1'
        }, {
        label: '누적 조세 부담율',
        data: [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.00, 0.01, 0.01, 0.01, 0.01, 0.01, 0.01, 0.01, 0.01, 0.01, 0.01, 0.01, 0.01, 0.02, 0.02, 0.02, 0.02, 0.02, 0.02, 0.02, 0.03, 0.03, 0.03, 0.03, 0.04, 0.04, 0.04, 0.05, 0.05, 0.05, 0.06, 0.06, 0.07, 0.07, 0.08, 0.09, 0.09, 0.10, 0.11, 0.12, 0.13, 0.14, 0.15, 0.16, 0.17, 0.19, 0.20, 0.22, 0.23, 0.25, 0.27, 0.29, 0.31, 0.34, 0.36, 0.39, 0.43, 0.46, 0.50, 0.55, 0.61, 0.67, 0.74, 0.84, 0.98, 1.00],
        borderColor: 'rgb(255, 0, 0)',
        pointRadius: 0,
        borderWidth: 1,
        yAxisID: 'y2'
      }]
    },
    options: {
        scales: {
            'y1': {
                beginAtZero: true,
                display: true,
                title: {
			    	display:true,
				    text:'(단위:만원)'
			    },
                type: 'linear',
                position: 'left'
            },
            'y2': {
                beginAtZero: true,
                display: true,
                title: {
			    	display:true,
				    text:'(%)'
			    },
                type: 'linear',
                position: 'right',
                ticks: {
                    callback: function(value) {
                        return (value * 100) + '%';
                    }
                }
            }
        }
    }
  });
</script>

<ol type ="1">
    <li>참고자료</li>
        <ul type ="SQUARE">
            <li><A href="https://www.data.go.kr/data/15082063/fileData.do">국세청_근로소득 백분위(천분위) 자료</A></li>
            <li><A href="https://www.alio.go.kr/mobile/statistics/employeeAvg.do?">공공기관 직원 평균보수</A></li>
        </ul>
    <li>그래프 작성 도구</li>
        <ul type ="SQUARE">
            <li><A href="https://www.chartjs.org/">Chart.js</A></li>
        </ul>
</ol>