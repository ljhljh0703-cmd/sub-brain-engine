# LLM Wiki Starter: The Dual-Engine Intelligence Framework

> "영감을 자산으로, 파편을 지능으로. 나만의 커스텀 LLM Wiki를 구축하는 가장 완벽한 프로토콜."

## 🚀 Overview
본 레포지토리는 고밀도 지식 베이스인 **LLM Wiki**를 구축하기 위한 핵심 아키텍처와 운영 지침을 제공합니다. Andrej Karpathy의 행동 원칙과 Dual-Engine(Gemini/Claude) 오케스트레이션 로직을 기반으로 설계되었습니다.

---

## 🛠️ Setup Guide (설치 및 세팅)

본 시스템을 가동하기 위한 OS별 필수 도구 설치 가이드입니다.

### 1. Obsidian (지식 보관소) 설치
- **macOS**: [공식 다운로드](https://obsidian.md/download)에서 `.dmg` 파일을 받거나 터미널에서 `brew install --cask obsidian` 명령어로 설치합니다.
- **Windows**: [공식 다운로드](https://obsidian.md/download)에서 `.exe` 파일을 받아 설치합니다.

### 2. Claude CLI (권위 엔진) 세팅
- **macOS**:
    1. Node.js 설치: `brew install node`
    2. CLI 설치: `npm install -g @anthropic-ai/claude-code`
    3. 실행 및 인증: `claude` 입력 후 API 키 등록
- **Windows**:
    1. Node.js 설치: [nodejs.org](https://nodejs.org/)에서 LTS 버전 설치
    2. PowerShell(관리자) 실행: `npm install -g @anthropic-ai/claude-code`
    3. 실행 및 인증: `claude` 입력 후 API 키 등록

### 3. Gemini CLI (데일리 엔진) 세팅
- **macOS**:
    1. 설치: `npm install -g @google/gemini-cli`
    2. 환경 변수 등록: `export GOOGLE_API_KEY='당신의_키'` (`~/.zshrc` 추천)
    3. 실행: `gemini`
- **Windows**:
    1. 설치: `npm install -g @google/gemini-cli`
    2. 환경 변수 등록: 시스템 설정의 '환경 변수'에서 `GOOGLE_API_KEY` 추가
    3. 실행: `gemini`

---

## 🛠️ Core Engine (The Dual-Engine Logic)
- **Daily Engine (Gemini)**: 실시간 지식 수집(Ingest), 디벨롭, 반복 작업을 수행하는 기동 유닛.
- **Authority Engine (Claude)**: 지식의 무결성 검증 및 SSOT(Single Source of Truth) 잠금을 담당하는 권위 유닛.

## 📥 Getting Started (Onboarding)
1. **Repo Star**: 이 레포지토리에 'Star'를 눌러 지지해 주세요.
2. **Purpose Inquiry**: [온보딩 페이지](https://ljhljh0703-cmd.github.io/sub-brain-engine/)에 접속하여 위키의 목적을 정의하십시오.
3. **Initial Setup**: 안내에 따라 디렉토리 구조를 생성합니다.
4. **First Ingest**: 첫 번째 지식을 입력하여 복리 성장을 시작하십시오.

---
*Inspired by Sub-brain Intelligence. Built for Collective Wisdom.*
