<div align="center">
    <img src="./assets/logo.png" alt="preview" width="320px">
    <br />
    <h2>言君(Genkun) - 당신의 언어 훈련 파트너</h2>
</div>

このプロジェクトのREDMEは日本語と韓国語で提供いたします。
<br>
이 프로젝트의 README는 한국어와 일본어로 제공됩니다.

- [日本語 (Japanese)](README.md)
- [한국어 (Korean)](README.ko.md)

<br/>

[![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)](https://nestjs.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)](https://reactjs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)

<br />

## 📋 목차

1. [서비스 소개](#-서비스-소개)
2. [기술 스택](#-기술-스택)
3. [시스템 아키텍처](#-시스템-아키텍처)
4. [레포지토리](#-레포지토리)
5. [주요 기능](#-주요-기능)
6. [서비스 화면](#-서비스-화면)
7. [앞으로의 계획](#-앞으로의-계획)

<br />

## 🎯 서비스 소개

### AI 기반 음성 분석으로 면접 답변을 객관적으로 점검하는 언어 훈련 웹 서비스

**言君(Genkun)**은 음성 파일을 업로드하면 **AI가 발화 내용을 분석**하고, **면접 관점의 피드백**을 제공하는 언어 훈련 웹 서비스입니다.

- 내 발음은 정확한지
- 말버릇은 없는지
- 이 답변이 면접관에게 자연스럽게 들리는지

혼자 연습하며 확인하기 어려웠던 부분을 데이터 기반으로 피드백합니다.

<br />

## 💡 주요 기능
- 음성 파일 업로드 및 AI 기반 발화 분석
- 면접 관점의 구조적 피드백 및 개선 제안
- 타임라인 기반 음성/분석 결과 재확인
- 세션 단위 연습 기록 관리

<br />

## 🛠 기술 스택

### Frontend
![React](https://img.shields.io/badge/React-18.x-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=flat-square&logo=vite&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-1.x-CC6699?style=flat-square&logo=sass&logoColor=white)

### Backend
![NestJS](https://img.shields.io/badge/NestJS-11.x-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-7-DC382D?style=flat-square&logo=redis&logoColor=white)

### Infra
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)


<br />

## 🏗 시스템 아키텍처

### 전체 시스템 구조

![system-architecture](./assets/system-architecture.png)

<br />

## 📂 레포지토리

- **Backend**: [AI 음성 분석 API 서버](https://github.com/GenKun-Ai/interview-analyzer)
- **Frontend**: [음성 업로드 및 분석 결과 UI](https://github.com/GenKun-Ai/interview-analyzer-web)

<br />

## ✨ 서비스 화면

### 1. 🎤 음성 파일 업로드 및 AI 기반 발화 분석

- 세션 단위로 음성 파일 업로드
- 업로드 후 자동 분석 진행

<table>
    <tr>
        <td align="center">
            <img src="./assets/file.gif" alt="업로드" width="400px"/>
        </td>
        <td align="center">
            <img src="./assets/completed.gif" alt="업로드 완료" width="400px"/>
        </td>
    </tr>
</table>

<br />

### 2. 🤖 면접 관점의 구조적 피드백 및 개선 제안

- 답변 구조 및 말하기 습관에 대한 피드백 제공
- 개선 포인트를 한눈에 확인

<img src="./assets/feedback.gif" alt="피드백" width="800px"/>
<br />

### 3. 🎵 타임라인 기반 음성과 분석 결과 재확인

- 음성과 분석 결과를 시간 축 기준으로 재확인
- 특정 발화 구간을 선택해 다시 듣기 가능

<img src="./assets/audio.gif" alt="분석 결과" width="800px"/>
<br />

### 4. 📊 연습 기록 관리

- 세션별 연습 기록 저장
- 이전 연습과 비교 가능

<img src="./assets/sessions.gif" alt="연습 기록" width="800px"/>
<br />

## 🚧 앞으로의 계획

### 기능 확장
- [ ] **사용자 인증 및 연습 기록 고도화** (JWT)
- [ ] **실시간 진행 상황 알림**
- [ ] **분석 결과 시각화** (차트, 그래프)
- [ ] **음성 비교 기능** (이전 연습과 비교)

### 기술 개선
- [ ] **CI/CD 파이프라인 구축** (GitHub Actions)

### 인프라
- [ ] **AWS 배포** (ECS, RDS, ElastiCache)
- [ ] **모니터링 시스템** (Prometheus, Grafana)


<br />


## 👤 개발자

**gwan**
- GitHub: [@ias-kim](https://github.com/ias-kim)
- Email: abcqkdnxm@g.yju.ac.kr


<br />

