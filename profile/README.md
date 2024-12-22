# 🤖 실감응용인공지능 프로젝트 - Emergency 🚨

<p align="center">
  🚑 응급실 및 병원 AI 요약 서비스 웹/앱 - 이머전시 (Emergency) 🚑
</p>

## 📝 서비스 소개
- 대한민국 응급의료의 중요한 이슈 중 하나인 ‘응급실 뺑뺑이’ 해결을 위한 응급실 요약 AI 서비스입니다
- 사용자가 현재 위치와 불편한 부위를 입력하면 AI가 공공 데이터 포털의 전국 응급실 데이터를 바탕으로 사용자의 증상에 맞는 진료가 가능한 가장 가까운 응급실을 요약하여 추천해주는 것이 주기능입니다

### 프로젝트 개요

- 이 프로젝트는 AI 기술과 공공 데이터를 융합하여 응급 의료 서비스의 접근성과 사용자 경험을 혁신적으로 향상시키기 위한 시스템을 개발한 것입니다
- 사용자가 입력한 증상에 맞춰 가장 적합한 응급 의료 기관을 추천하고, AI를 활용하여 의료 정보를 효율적으로 요약하고 전달하는 디지털 헬스케어 시스템입니다

### 목표

- AI 기반 자연어 처리 기술을 활용하여 사용자의 증상에 맞는 응급 의료 기관을 추천합니다
- 공공 데이터 API를 통해 실시간으로 응급 의료 기관 정보를 제공하고, 이를 AI가 자동으로 요약하여 사용자에게 전달합니다
- 사용자 맞춤형 의료 정보 제공을 통해 응급 상황에서도 신속하고 정확한 결정을 내릴 수 있도록 돕습니다
- AI가 사용자와 상호작용하며, 사용자에게 공감하고 필요한 정보를 제공합니다

### 주요 기능

- 사용자 증상 분석 및 추천 : 사용자가 입력한 증상을 분석하여 가장 적합한 응급 의료 기관을 추천해줍니다
- 의료 데이터 요약 : 방대한 양의 공공 의료 데이터를 AI가 자동으로 분석하고 요약하여, 사용자에게 필요한 정보를 간단히 제공해줍니다
- 위치 기반 응급실 추천 : 사용자의 위치를 기반으로 가장 가까운 응급 의료 기관을 추천해줍니다
- 사용자 맞춤 개인화된 의료 정보 제공 : 사용자의 과거 의료 기록과 증상 데이터를 바탕으로 맞춤형 정보를 제공해줍니다

## 개발 환경

### IDE

- VSCode (AI 개발)
- Google Colab (AI 모델 학습 및 배포)

### 사용 Python 라이브러리

- requests : HTTP 요청 및 대략적인 위치 조회 라이브러리

## 사용 API

### 1. 공공 데이터 API

- 국립중앙의료원_전국 응급의료기관 정보 조회 서비스 : 이 API를 사용하여 전국의 응급의료기관 정보(병원, 응급실 등)를 실시간으로 조회합니다.
  - API 엔드포인트 : `http://www.example.com/api/emergency`
  - 인증 방식 : API 키 기반 인증
  - 주요 기능 : 응급 의료 기관의 위치, 연락처, 진료 과목 등의 정보를 제공합니다.

### 2. AI 기반 의료 데이터 분석 API

- Gemini AI API : 이 API는 자연어 처리(NLP) 모델을 사용하여 의료 데이터를 분석하고 요약합니다. 주로 응급 의료 기관 정보와 관련된 대량의 데이터를 요약하는 데 사용됩니다.
  - API 엔드포인트 : `https://api.gemini.ai/summarize`
  - 인증 방식 : API 키 기반 인증
  - 주요 기능 : AI가 긴 의료 데이터를 요약하여 사용자가 쉽게 이해할 수 있도록 제공합니다.

### 3. 위치 기반 서비스 API

- Google Maps API : 사용자의 위치를 기반으로 가장 가까운 응급 의료 기관을 추천하기 위해 사용됩니다.
  - API 엔드포인트 : `https://maps.googleapis.com/maps/api/geocode/json`
  - 인증 방식 : API 키 기반 인증
  - 주요 기능 : 사용자의 위치를 기반으로 가장 가까운 병원이나 응급의료기관을 조회하고 추천합니다.


### 사용 방법

### 1. 코랩 환경에서 실행

이 프로젝트는 터미널 출력으로 마무리하여 코랩 환경에서 실행해볼 수 있습니다.

```
https://colab.research.google.com/drive/1oYMNX4PMDTy7F7N4AXup-Az0qqW03ZpP
```

## 🛠️ 사용 기술

### 🌏 FrontEnd
<p align="center">
	<img src="https://skillicons.dev/icons?i=html"><img src="https://skillicons.dev/icons?i=css"><img src="https://skillicons.dev/icons?i=js">
</p>

### 🌐 BackEnd
<p align="center">
	<img src="https://skillicons.dev/icons?i=spring"><img src="https://skillicons.dev/icons?i=java"><img src="https://skillicons.dev/icons?i=python"><img src="https://skillicons.dev/icons?i=gcp">
</p>

### 💾 Database
<p align="center">
    <img src="https://skillicons.dev/icons?i=mysql"><img src="https://skillicons.dev/icons?i=aws">
</p>

### 🚀 Deployment
<p align="center">
    <img src="https://skillicons.dev/icons?i=aws">
</p>

### 👥 Integrated Tool
<p align="center">
    <img src="https://skillicons.dev/icons?i=git"><img src="https://skillicons.dev/icons?i=github">
</p>

## ✨ 서버 플로우 동작

- 추가 예정

<table align="center" border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; border: 1px solid #ddd;">
  <tr>
    <td align="center" style="border: 1px solid #ddd;">
      <strong>서버 플로우</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="border: 1px solid #ddd;">
      <img src="image/백 플로우.jpeg" width="800px">
    </td>
  </tr>
</table>

## 💻 웹페이지 최종 동작

- 추가 예정

## 🎥 데모 시나리오 영상

- 추가 예정

