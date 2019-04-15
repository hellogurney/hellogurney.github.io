---
date: 2019-1-1
title: "Applied Predictive Modeling(실전 예측 분석 모델링)을 시작하며"
excerpt: "실전 예측 분석 모델링 요약 정리, R, 머신러닝"
author_profile: false
tags:
  - books
  - R
categories:
  - Machine Learning
header:
  image:
---

**Applied Predictive Modeling(실전 예측 분석 모델링) - Max Kuhn, Kjell Johnson** [책](https://book.naver.com/bookdb/book_detail.nhn?bid=12812347)    
**일시** : 2019.1.1 ~  
**주제** : 전반적인 예측 모델 과정(Machine Learning Processing)  
**짧은평** : 아래 내용은 책 + 개인 생각이다.   
좋은 책을 번역한 출판사와 옮김이에게 감사하다. 아쉬운 점이 있다면 번역서 상태가 좋지 못하다. 수식 오타, 오역이 많다. 원서를 구입해 함께 보고 있다. 이럴거면 왜 번역서를 구입 했을까하는 아쉬움이 남는 책이다.  

## 1장 시작하며(Introduction)
머신러닝, 인공지능, 패턴인식, 데이터 마이닝, 지식추론 등 각 분야에서 서로 다른 관점과 도구를 사용해 문제에 접근했다. 문제의 목적은 동일하다. 정확한 예측을 하는 것이다.!
이 책에서는 위의 용어들을 `예측 모델` 로 통칭했다.  

> `Data → Predictive Modeling`  
예측모델 : 정확한 예측값을 생성하기 위한 수학적 도구나 모델을 개발하는 절차

## **예측 vs 해석**
수 많은 메일 Data를 가지고 스팸 메일을 분류하는 예측모델을 만들었다.  
어느날 예측모델에 '안녕하세요 김미경입니다.'라는 이메일이 들어왔다.  
모델은 '안녕하세요 김미경입니다.' 메일을 스팸으로 처리했다.  
여기서 두 가지 생각을 해볼 수 있다.  
1. 메일을 정확하게 스팸으로 분류했는가? (예측)  
2. 왜 메일을 스팸으로 분류했는가? (해석)  

서비스 회사 입장에선 예측이 중요하고, 호기심 많은 사람이라면 왜 스팸으로 처리했는지 궁금할 것이다.  

다른 예를 들어보자.  
마이너리티 리포트 처럼 범죄자 예측모델이 있다. (물 속 예언가가 아니라 데이터를 학습한 컴퓨터가 한다.)  

'장발장' 이란 사람이 내일 빵을 훔친다고 모델이 알려줬다.  

1. '장발장'이 내일 정말 빵을 훔쳤는가? (예측)  
2. 왜 '장발장' 내일 빵을 훔친다고 알려주는가? (모델)  
> "장발장, 당신은 미래절도범이야 체포하겠어!"  
"예?"  

예측, 해석 무엇을 선택해야 하는가?  
두 마리 토끼를 다 잡고 싶지만 아쉽게도 현재까지 예측과 해석은 Trade-Off 관계이다.  
**높은 정확도를 가진 모델은 해석이 어렵다.**  
**해석하기 쉬운 모델은 정확도가 낮다.**   

정답은 없다.  
문제 정의, 비즈니스 모델, 목적에 맞게 case by case  

---

## 개요

이 책은 4개의 Part로 구성되어 있다.

## Part 1 일반 전략(General Stategies)
- 2장 예측 모델링 과정 훑어보기(A Short Tour of the Predictive Modeling Process)
- 3장 데이터 전처리(Data Pre-processing)
- 4장 과적합과 모델 튜닝(Over-Fitting & Model Tuning)

## Part 2 회귀 모델 (Regression Models)
- 5장 회귀 모델 성능 측정(Measuring Performance in Regression Models)
- 6장 선형 회귀와 이웃 모델들(Linear Regression and Its Cousins)
- 7장 비선형 회귀 모델(Nonlinear Regression Models)
- 8장 회귀 트리와 규칙 기반 모델(Regression Trees and Rule-Based Models)
- 9장 용해도 모델 정리(A Summary of Solubility Models)
- 10장 사례 연구 : 콘크리트 혼합물의 압축 강도(Case Study: Compressive Strength of Concrete Mixtures)

## Part 3 분류 모델 (Classification Models)
- 11장 분류 모델 성능 측정(Measuring Performance in Classification Models)
- 12장 판별 분석 및 기타 선형 분류 모델(Discriminant Analysis and Other Linear Classification Models)
- 13장 비선형 분류 모델(Nonlinear Classification Models)
- 14장 분류 트리와 규칙 기반 모델(Classification Trees and Rule-Based Models)
- 15장 보조금 지원 모델 살펴보기(A Summary of Grant Application Models)
- 16장 심각한 클래스 불균형 처리하기(Remedies for Severe Class Imbalance)
- 17장 사례 연구 : 작업 스케줄링(Case Study: Job Scheduling)

## Part 4 그 외 고려할 사항(Other Considerations)
- 18장 예측 변수 중요도 측정하기(Measuring Predictor Importance)
- 19장 특징 선택 입문(An Introduction to Feature Selection .)
- 20장 모델 성능에 영향을 미치는 요인(Factors That Can Affect Model Performance)
