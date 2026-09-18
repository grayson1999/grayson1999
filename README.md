<div align="center">

      <!-- Header Banner -->
      <img src="https://capsule-render.vercel.
  app/api?type=waving&color=auto&height=180&section=header&text=Grayson's%20Dev%20Space&fontSize=38&animation=fadeIn&fontAlignY=38" width="100%" />

      <!-- Dynamic Typing Subtitle -->
      <a href="https://github.com/Grayson1999">
        <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=3B82F6&center=true&vCenter=true&width=620&lines=AI+
  Agent+%26+System+Platform+Engineer;nepes+Corp.+%7C+LLM+Orchestration+%26+Platform+Arch;Search+Optimization+(BM25F+%2B+Vector)+%7C+SSAFY+13th" alt="Typing SVG" />
      </a>

      <br/>

      <!-- Highlights & Quick Badges -->
      <img src="https://img.shields.io/badge/Career-nepes%20(AI%20Agent%20%26%20Platform)-1E3A8A?style=flat-square&logo=target&logoColor=white" />
      <a href="https://www.ssafy.com"><img src="https://img.shields.io/badge/Activity-SSAFY_13기_(1학기_수료)-00b894?style=flat-square" /></a>
      <a href="https://www.viva100.com/main/view.php?key=20240726010008085"><img src="https://img.shields.io/badge/Award-최우수상-orange?style=flat-
  square&logo=trophy&logoColor=white" /></a>
      <a href="https://www.notion.so/24ef1b1598de4ecb9f6035fd9cc24ddb?pvs=21"><img src="https://img.shields.io/badge/Paper-생체_정보_측정_연구-blue?style=flat-
  square&logo=googledocs&logoColor=white" /></a>
      <a href="https://www.q-net.or.kr/crf005.do?id=crf00503&jmCd=1320"><img src="https://img.shields.io/badge/License-정보처리기사-7952B3?style=flat-square" /></a>
      <img src="https://img.shields.io/badge/License-SQLD-009688?style=flat-square" />

    </div>

    <br/>

    ## 📌 About Me

    - 💼 **Career** : **nepes (네패스)** | AI Agent & 시스템 플랫폼 엔지니어
      - 사내 AI Agent 플랫폼 3계층(Core-MCP-Work) 아키텍처 단독 설계 및 배포
      - 하이브리드 검색 엔진(자체 BM25F + pgvector) 개발 및 형태소 분석 지연 개선(4.5s ➔ 1.6s)
      - 레거시 팩토리 운영 플랫폼 20여 종 화면의 Vue 3 ➔ Next.js 무중단 점진 전환
    - 🎓 **Education & Activity** : **SSAFY 13기** (1학기 수료)
    - 🏆 **Award** : [공모전 최우수상 수상 기사](https://www.viva100.com/main/view.php?key=20240726010008085)
    - 📝 **Paper** : [영상처리 기반 생체 정보 측정 방법 구현 및 분석 (Notion)](https://www.notion.so/24ef1b1598de4ecb9f6035fd9cc24ddb?pvs=21)
    - 📜 **Certificates** : 정보처리기사, SQLD (SQL Developer)
    - ✍️ **Tech Blog** : [컴공돌멩이 블로그](https://comgongstone.site) 운영 중

    <br/>

    ## 🚀 Featured Engineering Projects

    ### 1. 🤖 사내 FAQ 및 업무요청 자동화 AI Agent 플랫폼
    > **반복 문의 대응과 업무요청서 작성 부담을 단일 워크플로우로 해결한 3계층 AI Agent 플랫폼 (단독 아키텍처/개발)**
    - **Architecture**: `Chatbot Core` - `Search MCP` - `System Integration MCP`로 분리하여 권한 캡슐화 및 타 사업부 이식 구조 구축
    - **Search Engine**: PostgreSQL 랭킹 한계를 보완한 **자체 다중 필드 BM25F** 직접 구현 + 질의 유형별 검색 분기 (검색어형 Hit@1 95%)
    - **Performance**: 짧은 수명 인스턴스의 형태소 분석기 초기화 병목을 규명하고 웜업 적용을 통해 **검색 왕복 지연 64% 단축 (4.5s ➔ 1.6s)**
    - **Reliability**: 비생성형 FAQ 원문 제공 구조로 **골든셋 즉답 오답률 1%대 유지** 및 구조화된 태그 기반 컨텍스트 분리로 **주제 오염 버그 해결**
    - **Impact**: 본사 및 관계 사업부 2곳 운영 배포, 감사 로그 기준 **4,000건 이상의 질의 안정 처리**

    ---

    ### 2. 🏭 제조기업 방문·출입 및 환경안전 운영 플랫폼
    > **단일 레거시 모놀리스를 3개 전용 시스템으로 분리하고 운영 중단 없이 Next.js로 점진 전환 (단독 담당)**
    - **Migration**: 20여 개 핵심 화면을 Vue 3에서 Next.js/TypeScript로 데이터 증분 동기화와 함께 **무중단 점진 마이그레이션**
    - **AI Agentic Search**: 최신 법령 반영 지연을 막기 위해 벡터 DB/RAG를 과감히 배제하고, **공공 API 직결 + Agentic 목차 탐색 구조** 설계
      - 골든셋 평가 결과 **인용 정확도 96%대**, 평가 범위 내 **환각(Hallucination) 0건** 달성
    - **DevOps**: AWS EC2, 와일드카드 SSL 전 구간 HTTPS 적용 및 롤링 무중단 배포 체계 정립
    - **Impact**: 10개월간 300건 이상의 요청 처리(완료율 96%), **월 10만 회 화면 이용** 및 **4,000명 이상의 외부 사용자** 안정 지원
    
    ---
    
    ### 3. 🔍 특허 아이디어 사전진단 AI Agent (R&D)
    > **연구원의 구어체 메모에서 특허 출원 가치와 보완 방향을 제시하는 선행기술 조사 Agent 방법론 검증**
    - **Root-Cause Analysis**: 8건의 독립 실험을 통해 검색 실패의 본질이 엔진 연산자가 아닌 **'일상어와 특허 문헌의 어휘 격차'**임을 규명
    - **Hallucination Defense**: 기존 데모의 허위 특허번호-제목 결합(날조) 문제를 발견하고, 실제 DB 교차검증 기반의 **Agent 반복 탐색**을 채택하여 **인용 실재성·주제 일치
  100% 확보**

    <br/>

    <div align="center">
      <a href="detail.md">
        <img src="https://img.shields.io/badge/📂_전체_프로젝트_상세_포트폴리오_보러가기-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="View Full Portfolio" />
      </a>
    </div>

    <br/>

    ## 🛠️ Tech Stack

    ### 🤖 AI / Agent & Search
    <p>
      <img src="https://img.shields.io/badge/AWS_Bedrock_AgentCore-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" />
      <img src="https://img.shields.io/badge/FastMCP-8A2BE2?style=flat-square&logo=dependabot&logoColor=white" />
      <img src="https://img.shields.io/badge/BM25F_Search-FF6F00?style=flat-square" />
      <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Cohere_Rerank-39594C?style=flat-square" />
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
    </p>
    
    ### ⚙️ Back-End & Runtime
    <p>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white" />
    </p>

    ### 💻 Front-End
    <p>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" />
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
      <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
    </p>

    ### 🗄️ Database & Cloud / DevOps
    <p>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
      <img src="https://img.shields.io/badge/AWS_(EC2_·_S3_·_Cognito)-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
    </p>

    <br/>

    ## 📊 Stats & Problem Solving

    <div align="center">
      <table>
        <tr>
          <td align="center" width="50%">
            <a href="https://solved.ac/bbt1250">
              <img height="180" src="http://mazassumnida.wtf/api/v2/generate_badge?boj=bbt1250" alt="Solved.ac Profile" />
            </a>
          </td>
          <td align="center" width="50%">
            <a href="https://github.com/Grayson1999">
              <img height="180" src="https://github-readme-stats.vercel.
  app/api?username=Grayson1999&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
            </a>
          </td>
        </tr>
      </table>
    </div>

    <br/>

    ## 📬 Contact

    <div align="center">
      <a href="mailto:bbt1250912@gmail.com">
        <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
      </a>
      <a href="https://comgongstone.site">
        <img src="https://img.shields.io/badge/Blog-20C997?style=for-the-badge&logo=tistory&logoColor=white" alt="Tech Blog" />
      </a>
      <a href="https://github.com/Grayson1999">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
      </a>
      <a href="https://www.instagram.com/seun9_99">
        <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
      </a>
    </div>
