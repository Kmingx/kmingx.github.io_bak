---
layout: post
category: project
title: BMW Garage Startup Program
description: >
 [웍스컴바인 프로젝트]
sitemap: false
hide_last_modified: true
#image: /assets/img/project/pic04.jpg
accent_image: 
  background: url('/assets/img/project/bmwstartupfarage.gif') center/cover
  overlay: true
---
[GitHub Code Link](https://github.com/Kmingx/Acorn-Academy/tree/main/project/01.%EA%B0%9C%EC%9D%B8%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)
#### BMW Garage Startup란 ?
    BMW Startup Garage는 개발, 생산, 서비스 등의 부문에서 4차 산업 기술과 비전을 보유한 스타트업을 발굴하여
    수십조 달러 규모의 자동차 산업과 함께하는 파트너사를 선정하는 프로그램이다.
    주어진 기간동안 PoC 검증 기간을 거쳐 각 부문에서 최종 파트너사를 선정합니다.

#### 프로젝트 및 개요
    1. BMW 콜센터 상담 NLU 대시보드 개발
     -> 상담 이력을 NLU분석을 통해 고객의 주요 이슈를 한눈에 파악하도록 시각화와, 키워드 도출을 통해
        고객의 불만사항과 니즈를 파악하는 웹 대시보드 개발

    2. BMW 7시리즈 재구매 고객 예측
     -> 고객 데이터 분석을 통해 재구매 요인을 도출하고 예측 모델을 통해 고객의 구매 패턴을 예측하여
        타겟 마케팅을 하도록 제안 했습니다.
        
    기간 : 2021/09/01 ~ 2021/12/01
    인원 : 8명
    RNR : 데이터 전처리, 데이터 필터링, 불용어 사전 제작, 형태소 분석

#### Data Status
    CIC상담데이터, AS이용데이터, BMW구매내역, 드라이빙 이용내역 데이터 등
    전체 데이터 총 : 3,035,715 건

#### 데이터 전처리 과정
    1. 중복데이터 제거
    2. 이상치 확인 및 제거
    4. 맞춤법 검사 및 단일화
    3. 개인정보 가명처리 및 삭제
    4. 형태소 및 데이터 필터링

#### 데이터 처리 예시
![Full-width image](/assets/img/project/bmwgs_1.png){:.lead width="1000" height="100" loading="1"}

#### 형태소 분석
![Full-width image](/assets/img/project/bmwgs_2.png){:.lead width="1000" height="100" loading="1"}

#### 카테고리 분류 Kobert
![Full-width image](/assets/img/project/bmwgs_3.png){:.lead width="1000" height="100" loading="1"}

#### 대시보드 시연 영상
![Full-width image](/assets/img/project/bmw2.gif){:.lead width="1000" height="100" loading="1"}

#### 느낀점
    가장 기초적인 임무이면서 프로젝트의 가장 중요한 항목인 데이터를 핸들링하는 역할을 수행 하였습니다.
    임무를 수행함에 있어서 어려웠던 부분은 긴 문장의 상담내용을 처리하는 것이였습니다.
    처리과정에 있어서 업계에서 사용되는 전문적인 단어로 구성되어 있어 전반적인 업계 지식과 용어를 숙지한 후 작업을 했었습니다. 
    비록 프론트엔드, 벡엔드, DB설계, 머신러닝 개발등 뚜렷한 기여는 하지 못했지만 많은것을 배우고 경험을 한 프로젝트였습니다.
    
