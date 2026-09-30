# Literature Search — Claude Skill

문헌고찰을 위한 문헌검색을 Claude에서 단계별로 안내하는 학생용 스킬입니다. 연구질문과 검색전략을 정리하고, 검색 결과를 점검한 뒤 PDF 보고서로 저장합니다.

![Claude Skill](https://img.shields.io/badge/Claude-Skill-orange.svg)
![Student Version 2.4](https://img.shields.io/badge/Student-v2.4-blue.svg)

**[SKILL.md 다운로드](https://github.com/Jeongin-Choe-RN/literature-search-claude-skill/raw/refs/heads/main/SKILL.md)** · [파일 내용 보기](SKILL.md)

## 주요 기능

- **관심 주제에서 시작** — AI와 연구질문, 고찰 유형, 범위 및 사용할 데이터베이스를 확인
- **검색어 검토** — 핵심 개념, 동의어와 주제어를 검토하고 검색어를 선택
- **검색식 작성 지원** — AI가 제안한 검색식 초안을 검토하며 AND·OR의 역할과 DB별 검색 문법을 이해
- **두 가지 검색 경로** — 사용 가능한 PubMed 커넥터로 검색하거나, DB 웹사이트에서 직접 검색한 결과 파일을 업로드
- **학생이 먼저 결과 점검** — 표본 최대 10건의 관련성을 학생이 먼저 판단한 뒤 AI와 비교하고 검색전략을 수정
- **PDF 보고서 저장** — 검색전략, 검색 기록, 문헌 목록과 학습 기록을 PDF 보고서로 정리

## 다운로드 및 사용 방법

1. 위의 **SKILL.md 다운로드** 링크로 파일을 저장합니다. 파일 내용이 열리면 [파일 내용 보기](SKILL.md)에서 **Download raw file** 버튼을 사용합니다.
2. Claude의 새 대화에서 다운로드한 `SKILL.md`를 **파일로 첨부**합니다.
3. 관심 주제와 함께 다음과 같이 입력합니다.

   > 첨부한 스킬에 따라 문헌검색을 진행해 주세요. 관심 주제는 간호대학생의 수면과 스트레스입니다.

4. 연구질문·고찰 유형·DB를 확인하고, 검색어와 검색식 초안을 검토합니다.
5. 아래 두 경로 중 사용할 방법으로 검색합니다.
   - **PubMed 미연결:** PubMed 웹사이트에서 검색식을 실행하고 결과 파일(NBIB·CSV 등)을 내려받아 Claude에 업로드합니다.
   - **PubMed 연결:** Claude에서 PubMed 커넥터를 별도로 연결·활성화한 뒤 검색을 요청합니다.
6. 표본 최대 10건을 먼저 판단하고, AI의 검토와 비교해 필요한 부분을 수정합니다.
7. 생성된 PDF 보고서를 확인하고 저장합니다.

이 저장소는 영상에서 사용하는 **대화창 파일 첨부 방식의 `.md` 파일**을 제공합니다.

## 사용 시 유의사항

- **커넥터는 스킬 파일에 포함되어 있지 않습니다.** 실제 검색 가능 여부는 Claude 환경과 연결된 도구에 따라 달라집니다. 연결하지 않아도 DB 결과 파일을 업로드하여 진행할 수 있습니다.
- 검색식, 검색 건수와 문헌 정보는 실제 DB 및 원문과 대조해 확인하세요. AI가 제안한 주제어도 해당 DB에서 확인해야 합니다.
- **표본 점검은 검색전략을 개선하기 위한 과정입니다.** 정식 문헌선별, 자료추출 또는 질평가를 대신하지 않습니다.
- PDF 산출물을 받으려면 파일 생성 기능을 사용할 수 있어야 합니다. 생성이 불가능한 경우 스킬은 PDF 제공이 보류되었음을 안내합니다.
- 실제 연구에서는 연구질문에 맞는 DB 범위와 추가 검색 방법을 검토하세요. 수업 예시의 PubMed 검색만으로 포괄적인 검색이 완료되었다고 판단하지 않습니다.

## 라이선스

별도의 오픈소스 라이선스는 지정하지 않았습니다. 재배포·수정본 배포 등 이용 허락이 필요한 경우 저장소의 Issues에서 문의해 주세요.

## 제작자

**최정인 (Jeongin Choe)**

[nncj91@snu.ac.kr](mailto:nncj91@snu.ac.kr)

## 지도교수

**우경미 (Kyungmi Woo)** — 서울대학교 간호대학 부교수

ANDA Lab: https://andalab.snu.ac.kr/

## 감사의 말

이 도구는 AI 도구(Claude, Anthropic)를 활용하여 개발되었습니다. 도구의 설계와 개발은 최정인이 수행하였으며, 박소연은 사용 과정을 검토하고 개선 의견을 제공하였습니다.

---

# Literature Search — Claude Skill (English)

A Claude skill that guides students through literature searches step by step. Develop a research question and search strategy, review search results, and save PDF reports.

**[Download SKILL.md](https://github.com/Jeongin-Choe-RN/literature-search-claude-skill/raw/refs/heads/main/SKILL.md)** · [View the file](SKILL.md)

## Features

- **Start with a topic** — clarify the research question, review type, scope, and databases with AI assistance
- **Review search terms** — examine key concepts, synonyms, and controlled vocabulary
- **Build a search strategy** — review an AI-proposed query and understand AND, OR, and database-specific syntax
- **Two search routes** — use an available PubMed connector or upload results exported from a database website
- **Student-first result review** — judge the relevance of up to 10 sample records before comparing with AI and revising the strategy
- **PDF reports** — save the search strategy, search log, record list, and learning log

## Download & Usage

1. Download `SKILL.md` using the link above. If the text opens instead, use **Download raw file** on the [file page](SKILL.md).
2. Start a new Claude conversation and **attach the downloaded file**.
3. Enter your topic and a request such as:

   > Please follow the attached skill to guide my literature search. My topic is sleep and stress among nursing students.

4. Confirm the research question, review type, and databases, then review the proposed terms and query.
5. Choose a search route:
   - **Without a PubMed connector:** run the query on the PubMed website, export the results (e.g., NBIB or CSV), and upload the file to Claude.
   - **With a PubMed connector:** separately connect and enable the PubMed connector in Claude, then request a search.
6. Judge up to 10 sample records first, compare your judgments with AI feedback, and revise as needed.
7. Review and save the generated PDF reports.

This repository provides the **`.md` file attached directly to the conversation**, as demonstrated in the teaching videos.

## Usage Notes

- **The skill file does not include a connector.** Live search depends on the tools available in your Claude environment. Uploaded database exports provide an alternative route.
- Verify queries, result counts, and bibliographic information against the database and source publications. Check proposed controlled vocabulary in the relevant database.
- **Sample review diagnoses the search strategy.** It does not replace formal study screening, data extraction, or quality appraisal.
- PDF delivery requires file-generation capability. If unavailable, the skill reports that PDF delivery is pending.
- For an actual review, assess appropriate database coverage and supplementary search methods. A PubMed-only classroom example does not establish a comprehensive search.

## License

No separate open-source license has been specified. Please use this repository's Issues for permission requests such as redistribution or distribution of modified versions.

## Author

**Jeongin Choe (최정인)**

[nncj91@snu.ac.kr](mailto:nncj91@snu.ac.kr)

## Advisor

**Kyungmi Woo (우경미)** — Associate Professor, College of Nursing, Seoul National University

ANDA Lab: https://andalab.snu.ac.kr/

## Acknowledgements

This tool was developed with the assistance of AI tools (Claude, Anthropic). Jeongin Choe designed and developed the tool. Soyeon Park reviewed the usage process and provided suggestions for improvement.
