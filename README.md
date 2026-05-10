<div align="center">

# 김성연 · Seongyeon Kim

### `AI Engineer` · LLM · RAG · LangGraph · MCP

복잡한 도메인을 빠르게 흡수하고, 실전 서비스까지 밀어붙이는 AI 엔지니어입니다.<br/>
공공·금융·과학·전력·AdTech 도메인에서 **End-to-End RAG 파이프라인**과 **Agent 워크플로우**를 만듭니다.

[![Tech Blog](https://img.shields.io/badge/Tech_Blog-DD0B78?style=flat-square&logo=GitHub-Sponsors&logoColor=white)](https://seongyeon1.github.io/)
[![Email](https://img.shields.io/badge/ksy974498@gmail.com-EA4335?style=flat-square&logo=Gmail&logoColor=white)](mailto:ksy974498@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/seongyeon1/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Kirby's_Quest_RPG-FFA6C4?style=flat-square&logo=html5&logoColor=white)](https://github.com/seongyeon1)

</div>

---

## 🌱 About

LLM·RAG 기반 AI 애플리케이션을 **End-to-End**로 설계·구현합니다.
단순한 모델 호출이 아닌 **제품화 가능한 구조 설계 · 평가 자동화 · 성능 개선 사이클**을 전 주기로 다루는 데 몰입해왔습니다.

```yaml
focus:
  - RAG Pipeline (Hybrid Retrieval, Re-rank, Multi-turn)
  - LangGraph Agent · MCP · Tool Use
  - MLOps (Docker, K8s, Jenkins, ArgoCD)
based_in: Seoul, KR
years: 4+ (KDT → 학부 인턴 → Aiffel → Clabi → BrainCrew)
```

---

## 🏢 Now — BrainCrew · AI Engineer (`2025.09 ~`)

금융·Consumer·Enterprise·AdTech 도메인 RAG·Agent 시스템을 만들고 있습니다.

| Project | Domain | Highlights |
|---------|--------|------------|
| **IBK Capital** AI 여신 승인 | 금융 (On-Prem) | 처리시간 **70%↓** (3.5일→1일) · 비용 **₩4.7억/년 절감** |
| **LG Electronics** 라이프로그 RAG | Consumer | 정확도 **92%** · Context **85%↓** (Graph + Vector Hybrid) |
| **GS Caltex** Long-term Memory MCP | Enterprise | 사내 AI 솔루션 MISO 통합 · 사용자 컨텍스트 영속 저장·재호출 |
| **HSAD** 광고 기획서 자동 구조화 | AdTech | 비정형 PPT/PDF → 표준 스키마 매핑 |
| **braincrew-index** Org Repo Dashboard | Internal · DX | **2h 증분 인덱싱** · AWS Bedrock Claude **AI 요약** · contributor 커밋 → 팀 Lead/Contributed **자동 매핑** |

### 🧰 Internal Tools & OSS

> 팀 온보딩·운영·문서 생산성을 위한 도구들 — 직접 기획·구현·배포

- **[oh-my-slides](https://github.com/seongyeon1/oh-my-slides)** · [Live Demo](https://seongyeon1.github.io/oh-my-slides/) <sup>OSS</sup>
  자연어 프롬프트 → **애니메이션 HTML 프레젠테이션 + PPTX export** Claude Code 플러그인.
  **20개 큐레이션 디자인 프리셋** (Bold Signal · Dark Academia · Terminal Green · Bento Grid 등), 모든 슬라이드 `100dvh` 자동 피팅, `clamp()` 타이포 스케일, custom .pptx import, zero-dependency 단일 HTML 출력.

- **bc-ppt** · Braincrew 브랜드 PPT Skill
  4 variant (dark-a / light-b / internal-a / internal-b) × **13 레이아웃 고정**으로 브랜드 일관성 유지.
  **HTML + 편집 가능 PPTX 듀얼 출력** (placeholder 치환식, 이미지 PPTX 아님). `spec_lock.md` 재독 의무로 긴 덱 스타일 드리프트 방지, `page_rhythm` 태그(anchor/dense/breathing)로 슬라이드 리듬 제어.

- **Docker Log Monitor** · 실시간 컨테이너 장애 감지 (EC2 + systemd)
  Docker SDK로 stdout/stderr 스트림 구독 → 패턴 매칭 → **Slack 알림** (Webhook + **Bot API 스레드 모드**, traceback 전문 잘림 없이 전송).
  쿨다운 / Grace Period / 4xx 자동 필터로 노이즈 제거, **AWS Bedrock으로 에러 원인 자동 분류** (코드 결함 vs 외부 의존), 주간 리포트 + Slack Canvas 통계 게시.

- **Notion → 기술블로그 자동 배포** · Notion API → Markdown → 사내 기술블로그 CI/CD

---

## 📚 Selected Past Work

<details open>
<summary><b>Clabi · 전략기술연구소 AIOps 팀</b> · 연구원 <code>(2024.12 — 2025.08)</code></summary>

- **충청남도교육청** 초거대 생성형 AI — **Lead E2E** · group_id 대화 이력 · chunk depth 임베딩 · 부서 자동 매핑 · Jenkins+ArgoCD+K8s
- **대한전기협회 KEPIC AI** — 멀티턴 Re-rank · Function Calling 정보 병합으로 **Latency 40s → 15s**
- **동아사이언스 과학동아 AI** — Chroma → Milvus 이전 + 모듈형 LangChain 리팩토링 + CI/CD
- **경상북도교육청** — 캘린더 AI DB 설계 + 담당부서 메타데이터 매핑
</details>

<details>
<summary><b>Aiffel 리서치 과정</b> · Research Trainee <code>(2024.05 — 2024.11)</code></summary>

- [한국어 챗봇 from scratch](https://github.com/seongyeon1/Ko-Chatbots-From-Scratch)
- [한국어 영어 번역기 from scratch](https://github.com/seongyeon1/Ko-En-Translator-From-Scratch)
- [SiGenie](https://github.com/seongyeon1/SiGenie) — 선적서류 자동화 (B/L 검증, JsonOutputParser)
- [Ko-Threat-Detection](https://github.com/seongyeon1/Ko-Threat-Detection) — 한국어 위협 대화 분류 (앙상블 **F1 0.886**)
- [AI Medical Assistant](https://github.com/seongyeon1/AI-Medical-Assistant) — 질병 예측·병원 추천 (Ollama 로컬)
- [요양병원 보호자 안심 서비스](https://github.com/primer-genAI/NursingHome) — Flutter + LangChain RAG
</details>

<details>
<summary><b>중앙대 DILAB</b> · 학부 인턴 <code>(2022.08 — 2023.04)</code></summary>

- 근시퇴행 예측 / 보라매 병원 CAG 후 생존 분석
- 소아 응급환자 응급분류 모델 (T-test, 상관관계)
- 암 예후 예측 경진대회 + 매주 AI 논문 discussion
</details>

<details>
<summary><b>데이터 분석 학회 Dart-B</b> · 팀장 <code>(2023.03 — 2023.12)</code></summary>

- **2023 BDA 공모전 본선 진출** — CJ더마켓 프라임 회원 예측 (AUC **0.86**, F1 **0.81**)
</details>

---

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

**AI / LLM**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6F61?style=flat-square&logo=graphql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**DB / Vector DB**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=zilliz&logoColor=white)
![Chroma](https://img.shields.io/badge/ChromaDB-FFB800?style=flat-square&logo=chromadb&logoColor=black)

**MLOps / Infra**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Naver Cloud](https://img.shields.io/badge/Naver_Cloud-03C75A?style=flat-square&logo=naver&logoColor=white)

**Tools**
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Wandb](https://img.shields.io/badge/Wandb-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

---

## 🏆 Awards

| Tier | Date | Title | Project |
|------|------|-------|---------|
| 🥇 | 2024.09 | **KDT 해커톤 고용노동부장관상** | "이야기 보따리" — 노인 이야기 → 동화 변환 (LangChain·STT·FastAPI) |
| 🥇 | 2023.12 | **응용통계학과 공모전 최우수상** | "알려줘! 홈즈" — 채용공고 텍스트 마이닝 + GPT 인사이트 |
| 🥈 | 2025.03 | 사내 아이디어 경진대회 우수상 (Clabi) | Table 특화 finetuning sLLM |
| 🥈 | 2024.11 | DPG 해커톤 우수상 (업스테이지) | Pre-KTAS 응급환자 분류 (Solar + RAG) |
| 🥈 | 2023.06 | 경영경제대학 학술제 우수상 | [인공지능탐정단](https://github.com/seongyeon1/AI_Detective) — 합성 데이터 품질 평가 |
| 🥉 | 2025.03 | 사내 아이디어 경진대회 장려상 (Clabi) | 법령정보 특화 AI Agent |
| 🥉 | 2023.05 | 생산관리학회 공모전 장려상 (KOMIPO) | AI 통합 에너지 관리 플랫폼 |
| 🥉 | 2022.11 | NH투자증권 공모전 장려상 | VIP 분류·추천 시스템 |
| 🥉 | 2022.11 | 미래에셋증권 공모전 장려상 | Dinger 포트폴리오 (PPO 강화학습 리밸런싱) |

## 🎖️ Certifications

- **빅데이터 분석기사** · 과학기술정보통신부·통계청 (2024.07)
- **AICE Associate** · KT·한국경제신문 (2022.11) — [Open Badge](https://www.openbadge-global.com/ns/portal/openbadge/public/assertions/detail/L2N4T0lGZ2lDeFU1aVE1M3JRUnRnQT09)
- **데이터 분석 준전문가 (ADsP)** · 한국데이터산업진흥원 (2021.06)
- **Google Data Analytics** · [Coursera](https://coursera.org/share/fedd20f3b8ca74b9b0b4230703fa3e5d) (2024.08)
- **Machine Learning** · [Coursera](https://www.coursera.org/account/accomplishments/specialization/QRHSEKPLHHDB) (2023.08)
- **Google Cloud AI Study Jam** · Google (2024.10)

---

## 📊 GitHub

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-eight-theta.vercel.app/api?username=seongyeon1&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&card_width=450">
  <img alt="Seongyeon's GitHub Stats" src="https://github-readme-stats-eight-theta.vercel.app/api?username=seongyeon1&show_icons=true&theme=graywhite&hide_border=true&count_private=true&include_all_commits=true&card_width=450">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=seongyeon1&theme=tokyonight&hide_border=true&date_format=Y-m-j">
  <img alt="GitHub Streak" src="https://streak-stats.demolab.com?user=seongyeon1&theme=graywhite&hide_border=true&date_format=Y-m-j">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=seongyeon1&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&card_width=450">
  <img alt="Top Languages" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=seongyeon1&layout=compact&theme=graywhite&hide_border=true&langs_count=8&card_width=450">
</picture>

</div>

---

<div align="center">
<sub>"단순한 모델 호출이 아닌, 제품화 가능한 구조를 만듭니다."</sub>
</div>
