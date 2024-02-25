---
layout: post
category: project
title: 생성AI(ChatGPT) 활용한 컨텐츠 자동생성
description: >
 [개인 서브 프로젝트]
sitemap: false
hide_last_modified: true
#image: /assets/img/project/pic04.jpg
accent_image: 
  background: url('/assets/img/project/20240224_ChatGpt/Untitled.png') center/cover
  overlay: true
related_posts:
    - _posts/project/2021-06-15-BMW 신규 거점 분석.md
    - _posts/project/2021-09-01-BMW Garage Startup.md
    - _posts/project/2022-01-20-SNS데이터수집.md
---

# 생성AI(ChatGPT) 활용한 자동 컨텐츠 생성

### 개인 서브 프로젝트

생성형 AI을 활용하여 컨텐츠를 자동으로 생성하여 블로그에 업로드 하고자 했습니다.

너무나 바쁜 현대 사회 뉴스 읽을 시간 조차 없어 만들어진 뉴스레터..

뉴스를 요약해주는 점이 편리하지만 데이터의 양이 방대해지니 그 조차 읽기 벅차기 시작했습니다.

뉴스을 요약한 뉴스레터을 요약한 하면 지식의 깊이는 얕을 수 있으나 세상이 흘러가는 트렌드 파악은 가능하다고 생각했습니다.

요약에 요약본을 읽고 흥미로운 주제가 있다면 조금 더 찾아 보는게 더 효율적이지 않을까요 ?

기간 : 2023/02/02 ~ 2024/02/15

### 프로젝트 구상

![Untitled](/assets/img/project/20240224_ChatGpt/Untitled.png)

개인 프로젝트 구상은 다음과 같습니다.

1. 뉴스레터 요약 포스팅
    - 뉴스레터를 구독하여 Gmail로 컨텐츠를 수급 받습니다.
    - imaplib 라이브러리를 활용 하여 Gmail을 핸들링 합니다.
    - 수급 받은 데이터를 전처리 합니다.
    - ChatGPT API을 통해 해당 전처리한 데이터를 요약합니다.
    - Tistory API을 통해 재가공한 컨텐츠를 블로그에 업로드 합니다.
2. 창작 시 및 창작 그림 포스팅
    - ChatGPT API을 통해 시 주제를 생성 합니다.
    - 생성한 시 주제를 GPT을 통해 시 주제와 맞는 시를 창작 시킵니다.
    - 창작한 시를 기반으로 Dall-E 모델을 통해 이미지를 생성합니다.
    - Tistory API을 통해 생성된 시와 그림을 블로그에 업로드 합니다.
3. 일본어 학습 포스팅
    - ChatGPT API을 통해 일본어 문장을 생성 합니다.
    - 생성한 일본어 문장을 GPT을 통해 문장에 핵심 명사, 동사, 한자 등 학습을 서포트 할수 있는 해설을 생성 합니다.
    - 생성된 데이터를 Tistory API을 통해 블로그에 업로드 합니다.

### 뉴스레터 전처리

![Untitled](/assets/img/project/20240224_ChatGpt/Untitled1.png)

HTML 기반으로 날라오는 뉴스레터 Data을 GPT을통해 재가공 하기위해 데이터를 전처리 진행합니다.

![Untitled](/assets/img/project/20240224_ChatGpt/Untitled2.png)

HTML → Text로 전처리 진행 후 GPT로 본문 요약 
결과물

![Untitled](/assets/img/project/20240224_ChatGpt/Untitled3.png)

[https://cgom.tistory.com/40](https://cgom.tistory.com/40)

### 일본어 하루 1문장 학습하기 결과물 예

[https://cgom.tistory.com/39](https://cgom.tistory.com/39)