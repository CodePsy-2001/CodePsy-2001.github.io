---
title: "[심리검사] Test and Measurement 검사와 측정"
date: 2021-12-17 01:37:12 +0900
categories: [심리학, 필기]
tags: [심리검사및측정]
---

2021-2학기 서강대학교 심리검사및측정 수업의 필기자료입니다.



# Test and Measurement

- construct 구성개념 - 증명되거나 관찰된 일련의 유사한 행동으로부터 추론되는 추상적인 가상의 실체
  - ex) 사랑, 동기부여, 역량, 우울 등
  - latent variable 잠재변수라고도 불림
- indicators 지표 - 관찰된 행동은 구성개념의 표현으로 가정될 수 있다.
  - ex) 심리학자의 우울증 조사 / 구성개념: 우울함 / 지표: BDI점수
  - 이 지표가 좋은 지표인지는 어떻게 알 수 있을까?

- measurement instruments 측정 도구
  - Scale, Test, Inventory, Questionnaire - 종종 혼용되지만 구별 가능함





## 측정의 종류

### Scale 척도

- 주로 construct 구성개념에 관한 것
- 척도로 구성된 각 항목에 대해 올바른 응답이 따로 없고, 제시된 항목 중 가장 가까운 것을 고른다.
  - ex) 로젠버그 자존감 척도
    10개 항목 구성, 강한동의~강한비동의 4지선다, 5개는 긍정문, 5개는 부정문
    총점은 30점까지, 점수가 높을수록 높은 자존감의 지표이다

### Test 검사

- 주로 competence 역량에 관한 것

- 검사를 구성하는 각 항목에 대해 올바른 응답이 있다.
  - ex) SAT, TOEFL, 이외 다양한 지능검사
    한 테스트가 여러 하위 테스트로 구성되기도 한다.
    예를 들어, 웩슬러 지능검사는 VIQ 점수와 PIQ 검사의 합계이다.

### Inventory

- 주로 성격 특성, 직업 성향 등에 관한 것

- 정확한 답을 요구하지 않지만, 어떤 선택이 특정 진술에 대한 개인을 특정짓는 데 더 적합한지 알려준다.

  - ex) Beck's Depression Inventory

    21문항, 객관식, 항목당 0~3까지 값에서 서로 다른 심각도를 가진 4개의 문장
    총점이 높을수록 더 심각한 우울증 증상의 지표이다.

### Questionnaire 설문지

- 다양한 유형의 측정 도구(scale, inventory...)를 포함할 수 있다.
- 연구자들은 연구에 필요한 모든 척도, 검사, inventory 등을 포함하는 설문지를 작성한다.





## Measurement Error 측정 오차

- 고전적 검사 이론(Classical test theory)은 Measurement Error 측정 오차 개념에 바탕을 두고 있다.

- 측정 오차란? 측정 대상의 구성개념과는 전혀 관련이 없지만, 측정 점수에 영향을 미치는 것 
  - 관심 대상인 구성개념과 관련없는 다른 요인들의 효과의 결합
  - ex) BDI - 우울 말고도, 밤에 시끄러운 이웃이나, 이사한지 얼마 안됨 등의 요인이 영향을 미칠 수 있다.
- **X (observed score)  =  T (true score) + E (error)**
  - Xi =  Ti + Ei (i라는 사람 개인에 대해)
  - Xpi = Tpi + Epi (i라는 사람 개인에 대해, p라는 문항에 대해)



### CTT(Classical Test Theory)의 가정

- **E(Epi) = 0**
  - 오류 점수는 어떤 사람에게는 음수, 어떤 사람에게는 양수일 수 있지만, 평균을 내면 0이 된다.

- **Cov(Tpi, Epi) = 0, Corr(Tpi, Epi) = 0**
  - 어떤 문항의 실제점수가 그 문항의 오류점수에 영향을 미치지 않는다.

- **Cov(Tpi, Eqi) = 0, Corr(Tpi, Eqi) = 0, when p ≠ q**
  - 어떤 문항의 실제점수가 다른 문항의 오류점수에 영향을 미치지 않는다.

- **Cov(Epi, Eqi) = 0, Corr(Epi, Eqi) = 0**
  - 어떤 항목의 오류점수가 다른 문항의 오류점수에 영향을 미치지 않는다.



### 가정에 따른 응용

- **E(Xpi)** = E(Tpi + Epi) = E(Tpi) + E(Epi) = E(Tpi) + 0 **= E(Tpi)**
  - 따라서, CTT 가정이 충족되면, 관측점수가 실제점수와 같다고 볼 수 있다.

- **Var(Xpi)** = Var(Tpi + Epi) = Var(Tpi) + Var(Epi) + 2Cov(Tpi, Epi)
  = Var(Tpi) + Var(Epi) + 0 = **Var(Tpi) + Var(Epi)**
  - 따라서, CTT 가정이 충족되면, 관측점수의 분산은 실제점수와 오차점수의 분산의 합이다.

- **Cov(Xpi, Xqi)** = Cov(Tpi+Epi, Tqi+Eqi) = Cov(Tpi,Tqi) + Cov(Tpi,Eqi) + Cov(Epi,Tqi) + Cov(Epi,Eqi)
  = Cov(Tpi,Tqi) + 0 + 0 + 0 **= Cov(Tpi, Tqi)**
  - 따라서, CTT 가정이 충족되면, 두 문항의 관측점수의 공분산은 실제점수의 공분산과 같다.





## Reliability 신뢰도

- 얼마나 강하게 관측점수와 실제점수가 연관되어 있는지
  - 측정 방법을 신뢰할 수 있다 = 관측점수가 실제점수를 더 잘 반영한다
    측정 방법을 신뢰할 수 없다 = 관측점수가 실제점수보다 오류점수를 더 잘 반영한다

- 두 가지 방법이 가장 널리 사용됨 (모두 CTT 가정에 기초)
  - Reliability Index
  - Reliability Coefficient (더 자주 쓰임)



### Reliability Index

reliability index = true score(T) 와 observed score(X) 사이의 correlation

= Cov(Xi, Ti) / √(Var(Xi), Var(Ti)) = √(Var(Ti) / Var(Xi))

- 0과 1 사이의 값

-> 이것의 제곱인 Reliability Coefficient 를 사용하는 것이 더 해석하기 좋다.



### Reliability Coefficient

reliability coefficient = Var(Ti) / Var(Xi) = STD(T) / (STD(T) + STD(E))

- 오류점수의 분산이 높아질수록, 신뢰도가 낮아진다.

- 0과 1 사이의 값



### 그래서 신뢰도를 높이려면 어떻게?

- 고것은 다음 챕터에서~~
