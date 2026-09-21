
# 🏦 코스콤(Koscom) 2026 하반기 AI 엔지니어 과제 제출

## 📌 제출자 정보
- **이름**: 윤주영
- **제출일**: 2026년 9월 21일
- **프로젝트명**: koscom-ai-financial-agent

---

## 📄 제출 서류 및 발표 자료
- 📊 **발표 슬라이드 (PPT)**: [`Koscom_AI_Assignment_Submission.pptx`](./Koscom_AI_Assignment_Submission.pptx)
- 🎥 **2분 데모 영상 링크**: [YouTube/Vimeo 링크 입력]
- 🧪 **정량 평가 결과**: [`evaluation/metrics.json`](./evaluation/metrics.json)

---

## 🛠️ 주요 구현 성과
1. **Financial Hybrid RAG**: BM25 + Vector Search (Recall@5: 93.3%)
2. **MCP (Model Context Protocol) 연동**: 사내 API 및 주식 실시간 조회 Tool 구축
3. **보안 및 규제 준수**: API Key 마스킹, Docker 기반 On-Premise 격리 환경 구축

---

## 🚀 실행 방법 (Quick Start)
```bash
git clone [https://github.com/juy218-218/koscom-ai-financial-agent.git](https://github.com/juy218-218/koscom-ai-financial-agent.git)
cd koscom-ai-financial-agent
pip install -r requirements.txt
python main.py# koscom-ai-financial-agent
