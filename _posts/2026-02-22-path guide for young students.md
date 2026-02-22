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
<p><b>mermaid을 이용해 순서도 그리는 방법을 연습한 결과물</b></p>

```mermaid
flowchart TD

    %% 중학교 레벨
    subgraph MiddleSchool []
        direction LR
        A[중졸 검정고시]
        D[지방 중학교]
        F[수도권 일반 중학교]
    end

    %% 고등학교 레벨
    subgraph HighSchool []
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
    linkStyle 8 stroke:green,stroke-width:3px
    linkStyle 10,11 stroke:#ff6600,stroke-width:3px
```