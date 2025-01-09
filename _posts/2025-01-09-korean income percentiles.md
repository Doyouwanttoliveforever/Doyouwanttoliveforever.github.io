---
layout: single
title: "Income and Tax percentiles"
cagegories: 일상
tag: [소득, 세금, 한국]
author_profile: false
---
<div>
  <canvas id="myChart"></canvas>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<script>
  const ctx = document.getElementById('myChart');

  new Chart(ctx, {
    type: 'chart',
    data: {
      labels: ['100%내', '99%내'],
      datasets: [{
        label: '인당소득',
        data: [21.08,86.71],
        borderWidth: 1
      }]
    },
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>