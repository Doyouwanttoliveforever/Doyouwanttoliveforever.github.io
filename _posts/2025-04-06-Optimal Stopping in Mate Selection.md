---
layout: single
title:  "Optimal Stopping in Mate Selection"
cagegories: 일상
tag: [결혼, 남여, 나이]
author_profile: false
---
<p>2025-04-06 작성</p>

<p>언제 누구랑 만나 결혼하는게 가장 좋을까?<br/>
워낙 변수가 많으니 정답은 없다. 하지만 적당히 외부변수를 통제한 상황을 가정해본다면 도움이 될만한 조언을 찾을순 있다.</p>
<p><a href="https://horizon.kias.re.kr/6053/">최고의 배우자 찾기</a>라는 글을 읽어보면 직원을 채용하거나, 배우자를 정할때 도움이 된다.<br/>

<ol type ="A">
<li>전체 인원수의 37% 정도의 사람은 만나면서 감을 익히고, 일생의 동반자에게 필요한 자신의 기준을 설정하도록 한다. 그리고 그 이후의 사람 중에서 그때까지의 사람보다 더 좋은 사람을 만나게 되면 무조건 선택하는 전략이 최고의 배우자를 선택할 가능성이 가장 큰 전략이다.<br/>
즉, <mark>100명을 만날수 있으면 37명과 사궈본후 38번째 만나는 사람부터 앞서 만난 사람보다 괜찮은 사람이 있다면 스톱</mark><br/>
하지만 사람은 자신이 몇명이나 만날지 알수도 없고, 여러명을 만나볼수록 많은 시간과 돈이 낭비되니 실재론 이런식으로 배우자를 정하지 않는다.</li>
<li>따라서 감을 익히기 위해 만다는 사람들의 <span style="color:red;">분표를 사용하는 방법</span>을 대안으로 생각해볼만 한다.<br/>
<mark>상위10%이상되는 사람을 배우자로 정하기로 했다면 12%정도 사람으로 감을 잡은후 이후 정하면 되고, 상위 25%이상으로 더 낮추면 8%정도만 만나봐도 된다.</mark> 즉 탐색비용이 크게 줄어드는 셈이다.<sub><a href="#footnote1">1</a></sub><br/></li>

<img src="/assets/images\2025-04-06-Optimal Stopping in Mate Selection/number of possibilities checked.jpg" align="center"><br/>
<li>위에서 수학적으로 살펴본것과 달리 실재 사람들이 행동은 그렇지 않다는 연구도 있다.<sub><a href="#footnote2">2</a></sub><br/>
나이나 조건에 따라 노려볼수있는 최고의 배우자 수준(optimal thresholds)이 달라지는데 <mark>젊을 나이때는 어느정도 일정하게 높은 배우자 수준을 노려볼수 있으나 나이가 들수록 눈 높이를 낮추는게 필요하다. 특히 여자가 남자보다 더 빨리 희망이 줄어든다.</mark> 아래 그림처럼 optimal thresholds는 fixed then linear 형태로 변한다.<br/>
그리고 젊을수록 높은 수준의 배우자를 노릴 기회가 있는데도 낮은 수준의 사람과 결혼하는 경향도 많다.<br/>
</li>

<img src="/assets/images\2025-04-06-Optimal Stopping in Mate Selection/optimal thresholds for environment.jpg" align="center"><br/>
<img src="/assets/images\2025-04-06-Optimal Stopping in Mate Selection/choice behavior.jpg" align="center"><br/>

</ol>
<hr color="black"><br/>

<p>인지과학자, 심리학자들이 연구한 결과와 일반인이 상식과 크게 벗어나지 않는다.</p>
<ol type ="1">
<li>좋은 배우자 조건이라는게 뭔지 생각해 보자. 외모(뛰어난 얼굴과 체격, 큰키), 좋은 성격, 학력, 재력, 가족관계, 취미 등 셀수없이 많은 조건이 있다. 사람에 따라 살펴보는 우선순위가 다 다르고 포기할수 있는것과 그렇지 않은 것 사이에 갈등이 존재한다. '재산은 1천만원이상이면 되지만 키는 180cm이하가 되면 안된다.'처럼 특정 조건에 하한선을 정해두기도 한다.<br/>
따라서 자신이 만나고자 하는 이상형에 대한 조건 리스트를 만들어 포기할수 있는 것과 없는 것, 하한선을 정해두고 만나야 시간낭비를 하지 않는다. 물론 이전에 충분히 감을 잡았다는걸 전제로 한다.</li>
<li>어느사회나 결혼적령기라는게 있는데 이 말의 뜻은 사회적으로 그 시점까지 몸값이 올라가는 시기를 말한다. 이때 몸값은 임금을 포함한 외모, 출산가능성 등 총체적인 합을 의미한다. 과거에 비해 결혼적령기가 늦춰진 이유는 고임금 일자리를 구하기 위해선 학습기간이 길어졌고, 의료기술의 발달로 수명이 길어지고 외모관리가 가능하기 때문이다. 연예인이 결혼을 늦게하는것도 인기를 높여 몸값을 최대한 높이는 행동으로 이해할수 있다. 하지만 이런건 사회 전반적인 평균일뿐이니 각 개개인은 스스로를 평가하여 자신의 외모, 소득 등 모든 조건을 고려한 값이 어느 시점에 가장 높을지 생각해 봐야한다.</li>
<li>하지만 세상은 합리적으로 굴러가는 곳이 아니다. 결혼시장에 나오는 사람들은 대체로 주변 친구가 결혼하면서 나오기 시작한다. 적령기보다 먼저 결혼하는 사람은 복걸복인 경향이 많다. 즉 충분히 좋은 사람을 만날수 있어보이는데 어처구니 없는 사람을 만나는 경향이 있다는 말이다.<br>
아무튼 이런 친구들 옆에 있던 사람들이 결혼을 생각하면서 시장에 나오게 된다. 하지만 친구의 결혼을 보고 시장에 나오면 살짝 늦은 감이 있다.이미 적령기를 지난 케이스라는 말이다. 따라서 친구를 보고 결혼시장에 뛰어들기보다 선배를 보고 결혼시장에 뛰어드는게 더 바람직하다.</li>
<li>결혼적령기를 자났다면 눈높이를 빠르게 낮추는게 유리한다. 이는 위 논문에도 언급하고 있다.</li>
</ol>

<p><br/>
요약하자면,<br/>
<mark>결혼시장에서 자신의 값어치가 언제 최고점을 찍을지 생각해보고,<br/>
그전에 연예를 통해 감을 잡고,<br/>
이상형 배우자의 기준점(키 얼마이상, 학력 어느정도, 외모, 성격 등)을 정한다.<br/>
그 기준점을 참고하여 만나봤던 사람의 상위 <em>x</em>% 이상이면 결혼한다는 마음가짐을 가지고,<br/>
친구가 아닌 선배들이 결혼하는 시점에 배우자를 물색한다.<br/>
배우자 물색을 위해 좋은 양질의 집단(좋은 대학, 좋은 동네, 좋은 직장, 동네 아줌마가 아닌 검증된 좋은 중매업체 등)에서 만남을 거친다.<br/>
만일 몸값이 떨어진다면 과감히 눈높이를 낮춘다.</mark> </p>

<hr color="black"><br/>
<footer>
    <p id="footnote1" style="font-size:90%">
        각주 1: Peter M. Todd
, <a href="https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=cc746a31c176562f13ff8a7fdb9e9b9c9f7673e9">Searching for the next best mate</a>
    </p>
</footer>
<footer>
    <p id="footnote2" style="font-size:90%">
        각주 2: Michael D. Lee and Karyssa A. Courey, 
, <a href="https://link.springer.com/epdf/10.1007/s42113-020-00085-9?sharing_token=Rmqt5pM4G0XxZb9Y7Mp1Vfe4RwlQNchNByi7wbcMAY4ucv9ON5w8MIAm8ZLwbgw2Ky8kmygra3L_GEoqj8kRQSv_zze5sv6YjmyVSXonBVhZCJQdhGsdVylQNU0dVYLKh2_xNSBQA9XEEtM-1R5GsovxQCif3zLXNmP4d7vFk0Y%3D">Modeling Optimal Stopping in Changing Environments: a CaseStudy in Mate Selection</a>
    </p>    
</footer>