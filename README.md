# AGY Tutorial Workspace

## 참고 문서

### skills

* [anthropics/skills: Public repository for Agent Skills](https://github.com/anthropics/skills)
* [sickn33/antigravity-awesome-skills: The Ultimate Collection of 800+ Agentic Skills for Claude Code/Antigravity/Cursor. Battle-tested, high-performance skills for AI agents including official skills from Anthropic and Vercel.](https://github.com/sickn33/antigravity-awesome-skills/tree/main)


### NotebookLM MCP

* [PleasePrompto/notebooklm-mcp: MCP server for NotebookLM - Let your AI agents (Claude Code, Codex) research documentation directly with grounded, citation-backed answers from Gemini. Persistent auth, library management, cross-client sharing. Zero hallucinations, just your knowledge base.](https://github.com/PleasePrompto/notebooklm-mcp)
* [jackc1111/antigravity-notebooklm-mcp](https://github.com/jackc1111/antigravity-notebooklm-mcp/tree/main)
* [duykhanhbv-bit/notebooklm-mcp-antigravity: connect notebookLM to mcp server antigravity, opencode](https://github.com/duykhanhbv-bit/notebooklm-mcp-antigravity)

## 스킬 및 워크플로우 구조

- `.agent/`: 에이전트 설정 및 스킬/워크플로우 정의
    - `skills/`: 데이터 분석 등 특정 작업을 수행하기 위한 스킬 정의
    - `workflows/`: 반복적인 작업을 자동화하기 위한 워크플로우 정의