<div align="center">
    <img src="./assets/logo.png" alt="プレビュー" width="320px">
    <br />
    <h2>言君(Genkun) - あなたの言語トレーニングパートナー</h2>
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

## 📋 目次

1. [サービス紹介](#-サービス紹介)
2. [技術スタック](#-技術スタック)
3. [システムアーキテクチャ](#-システムアーキテクチャ)
4. [リポジトリ](#-リポジトリ)
5. [主な機能](#-主な機能)
6. [サービス画面](#-サービス画面)
7. [今後の計画](#-今後の計画)

<br />

## 🎯 サービス紹介

### AIによる音声分析で面接の受け答えを客観的にチェックする言語トレーニングウェブサービス

**言君(Genkun)**は、音声ファイルをアップロードすると**AIが発話内容を分析**し、**面接官の視点からのフィードバック**を提供する言語トレーニングウェブサービスです。

- 私の発音は正確か
- 話し方の癖はないか
- この答えは面接官に自然に聞こえるか

一人で練習しながらでは確認しにくかった部分を、データに基づいてフィードバックします。

<br />

## 💡 主な機能
- 音声ファイルのアップロードとAIによる発話分析
- 面接官の視点からの構造的なフィードバックと改善提案
- タイムラインに基づいた音声/分析結果の再確認
- セッション単位での練習記録の管理

<br />

## 🛠 技術スタック

### フロントエンド
![React](https://img.shields.io/badge/React-18.x-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=flat-square&logo=vite&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-1.x-CC6699?style=flat-square&logo=sass&logoColor=white)

### バックエンド
![NestJS](https://img.shields.io/badge/NestJS-11.x-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-7-DC382D?style=flat-square&logo=redis&logoColor=white)

### インフラ
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)


<br />

## 🏗 システムアーキテクチャ

### 全体システム構造

![system-architecture](./assets/system-architecture.png)

<br />

## 📂 リポジトリ

- **バックエンド**: [AI音声分析APIサーバー](https://github.com/GenKun-Ai/interview-analyzer)
- **フロントエンド**: [音声アップロードと分析結果UI](https://github.com/GenKun-Ai/interview-analyzer-web)

<br />

## ✨ サービス画面

### 1. 🎤 音声ファイルのアップロードとAIによる発話分析

- セッション単位で音声ファイルをアップロード
- アップロード後に自動で分析を進行

<table>
    <tr>
        <td align="center">
            <img src="./assets/file.gif" alt="アップロード" width="400px"/>
        </td>
        <td align="center">
            <img src="./assets/completed.gif" alt="アップロード完了" width="400px"/>
        </td>
    </tr>
</table>

### 2. 🤖 面接官の視点からの構造的なフィードバックと改善提案

- 回答の構造と話し方の癖に関するフィードバックを提供
- 改善点を一目で確認

<img src="./assets/feedback.gif" alt="フィードバック" width="800px"/>
<br />

### 3. 🎵 タイムラインに基づいた音声と分析結果の再確認

- 音声と分析結果を時間軸基準で再確認
- 特定の発話区間を選択して聞き直し可能

<img src="./assets/audio.gif" alt="分析結果" width="800px"/>
<br />

### 4. 📊 練習記録の管理

- セッション別の練習記録を保存
- 以前の練習と比較可能

<img src="./assets/sessions.gif" alt="練習記録" width="800px"/>
<br />

## 🚧 今後の計画

### 機能拡張
- [ ] **ユーザー認証と練習記録の高度化** (JWT)
- [ ] **リアルタイム進行状況の通知**
- [ ] **分析結果の視覚化** (チャート、グラフ)
- [ ] **音声比較機能** (以前の練習との比較)

### 技術改善
- [ ] **CI/CDパイプラインの構築** (GitHub Actions)

### インフラ
- [ ] **AWSへのデプロイ** (ECS, RDS, ElastiCache)
- [ ] **モニタリングシステム** (Prometheus, Grafana)


<br />


## 👤 開発者

**gwan**
- GitHub: [@ias-kim](https://github.com/ias-kim)
- Email: abcqkdnxm@g.yju.ac.kr


<br />
