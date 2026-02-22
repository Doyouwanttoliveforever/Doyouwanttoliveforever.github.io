---
layout: single
title: "path guide for young students"
categories: 일상
tag: [학생, 진로, 학교, 순서도]
author_profile: false
---
<head>
  
</head>
<p>2026-02-22 작성</p>


```mermaid
flowchart TD

    %% 중학교 레벨
    subgraph MiddleSchool [" "]
        direction LR
        A[중졸 검정고시]
        D[지방 중학교]
        F[수도권 일반 중학교]
    end

    %% 고등학교 레벨
    subgraph HighSchool [" "]
        direction LR
        B[고졸 검정고시]
        E[지방 고등학교]
        G[수도권 일반 고등학교]
        H[특성화고]
        I[마이스터고]
    end

    %% 이후 단계
    C[대학]
    J[취업]

    %% 연결 관계
    A --> B --> C
    D --> E --> C
    F --> G --> C
    F --> H --> C
    F --> I --> J --> C

    %% 화살표 색 변경
    linkStyle 0,1 stroke:red,stroke-width:3px
    linkStyle 2,3 stroke:blue,stroke-width:3px
    linkStyle 4,5 stroke:black,stroke-width:3px
    linkStyle 6,7 stroke:green,stroke-width:3px
    linkStyle 8,9,10 stroke:#A5FFC9,stroke-width:3px
```


```mermaid
flowchart TD

    %% 중학교 레벨
    subgraph MiddleSchool [" "]
        direction LR
        A[중졸 검정고시]
    end

    %% 고등학교 레벨
    subgraph HighSchool [" "]
        direction LR
        B[고졸 검정고시]
        E[지방 고등학교]
        G[수도권 일반 고등학교]
        H[특성화고]
        I[마이스터고]
    end

    %% 연결 관계
    A --> B
    A --> E
    A --> G
    A --> H
    A --> I

    %% 화살표 색 변경
    linkStyle 0 stroke:red,stroke-width:3px
    linkStyle 1,2,3,4 stroke:black,stroke-width:3px
```

```mermaid
flowchart TD

    %% 중학교 레벨
    subgraph MiddleSchool [" "]
        direction LR
        F[수도권 일반 중학교]
    end

    %% 고등학교 레벨
    subgraph HighSchool [" "]
        direction LR
        B[고졸 검정고시]
    end

    %% 연결 관계
    F --> B

    %% 화살표 색 변경
    linkStyle 0 stroke:black,stroke-width:3px
```

<p></p>
<hr class="wp-block-separator has-alpha-channel-opacity"/>

<p>검정고시 제도를 이용하면 학생 실력에 따라 중학교 3년과정, 고등학교 3년과정을 단축할수 있는 장점이 있으며, 검정고시 성적이 만점에 가깝다면 정시 뿐 아니라 수시를 통해서 대학진학도 가능하다.<br>
고졸검정고시로 인한 불이익이 우려된다면 중학교만 검정고시 제도를 이용하고 고등학교는 정규과정을 밟는것도 생각해볼수 있다.</p>

<p>서울, 경기도가 아닌 지방에서 중학교, 고등학교를 졸업할경우 지방대학 및 지역균형인재 육성에 관한 법률에 따라 대학진학 및 취업에 혜택을 받을수 있다.</p>
<p>특성화고나 마이스터고 진학시 좋은 내신성적을 얻는다면 9급공무원이나 공기업 취업시 유리하니 의과대나 명문대 진학을 염두에 두지않고 있다면 충분히 고려할만 하다. 취업 이후에도 이런 학생만을 위한 대학입학전형도 있어 진학의 길도 열려있다.</p>
<hr class="wp-block-separator has-alpha-channel-opacity"/>

<p></p>

<p><i>위 순서도 작성은 <A href="https://mermaid.js.org/">Mermaid</A>를 이용하였다.</i></p>
