# 강재민 | jmkang21212-wq

**AI Pipeline · Backend · LLM Fine-tuning · AX**

기획 실무에서 구현을 모른 채 기획하는 한계를 느끼고 개발을 시작했습니다.

AI로 만든 기능이 실제 서비스에서 쓸 수 있는지 측정하고 검증하는 일에 관심이 많습니다.

<!-- 포트폴리오·블로그 주소가 정해지면 아래 주석을 풀고 주소를 바꿔 주세요
[![Portfolio](https://img.shields.io/badge/Portfolio-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://example.com)
-->
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/jmkang212)

---

## About

- 건국대학교 기술경영학과 졸업
- 삼성 청년 SW·AI 아카데미(SSAFY) 15기 Python 트랙 수료 · 성적 우수상, 공통 프로젝트 우수상
- LG DX School (2025.06 ~ 2025.12)
- 크라우드웍스 전략기획팀, 카카오모빌리티 라스트마일사업에서 기획·데이터 기반 업무 개선 실무 후 개발로 전환
- 정보처리기사 · SQLD · ADsP · TOEIC 945

---

## Featured Projects

| Project | Description | Stack |
|---|---|---|
| [**LAIVE**](https://github.com/jmkang21212-wq/S15P11C204) | 1인 방송인을 위한 실시간 방송 보조 AI 콘솔입니다. 채팅 AI 서버 담당으로 KcELECTRA 8감정 분류를 ONNX로 서빙하고, 여론 분포는 개별 라벨이 아닌 확률 합산으로 계산했습니다. 실제 채팅 399만 건으로 목표 227 TPS를 산출한 뒤, 부하 테스트로 스레드풀 경합 병목을 찾아 스레드풀 조정과 int8 양자화(macro-F1 1.9점 하락 감수)로 217.6 TPS · p99 895ms · 오류율 0%를 확인했습니다. SSAFY 공통 프로젝트 우수상. | Python, FastAPI, KcELECTRA, ONNX Runtime, Redis, PostgreSQL |
| [**주만추**](https://github.com/SSAFY-jumanchu/jumanchu) | 근거 있는 투자 습관을 위한 모의투자 서비스입니다. 3인 팀에서 백엔드 단독 담당으로 국내·미국 약 4,090종목의 시세·재무 데이터를 적재하고, 주문 멱등성 2단 방어(선검사 + DB unique), 장중·장외 TTL을 나눈 시세 Cache-Aside를 구현하고, 점수 계산은 결정적 코드로 두고 LLM은 설명 문장 생성만 맡도록 분리했습니다. | Python, Django 5.2, DRF, JWT, PostgreSQL, Redis, KIS API, DART API, OpenAI |
| [**planetory**](https://github.com/baekseunghak/planetory) | TESS 관측 데이터로 외계행성 후보 신호를 탐색하고 분석 기록을 공유하는 웹 서비스입니다. 6인 팀에서 탐사 코어 백엔드를 맡았고, 기능명세서와 ERD를 작성하며 외부 카탈로그가 갱신되면 과거 판정을 재현할 수 없다는 점을 구현 전에 짚어 변경 이력 테이블을 먼저 정의했습니다. | Java 21, Spring Boot 4, JPA, PostgreSQL, Redis |
| [**MMP**](https://github.com/jmkang21212-wq/MMP) | Mattermost·GitLab 연동 로컬 MCP 서버입니다. 리뷰어가 없을 때를 대비해 팀에 도입했고, 열린 MR끼리의 충돌을 미리 보는 교차 MR 검사를 만들어 설정 키 중복을 병합 전에 정리했습니다. | Node.js, MCP, SQLite, GitLab API, Mattermost |
| [**VQA Fine-tuning**](https://huggingface.co/jmkang212/qwen3vl-32b-vqa-lora-full-grpo) | Qwen3-VL-32B를 QLoRA(4bit)와 GRPO로 파인튜닝해 정확도를 83%에서 93.26%로 높였고, 200개 팀 중 상위 20위에 들었습니다. | Qwen3-VL, QLoRA, GRPO, Hugging Face |

---

## Tech Stack

**Language**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**AI / ML**

![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Database / Cache**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Collaboration**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Mattermost](https://img.shields.io/badge/Mattermost-0058CC?style=flat-square&logo=mattermost&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

**Learning**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
