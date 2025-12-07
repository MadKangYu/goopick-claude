# goopick-claude

Claude Desktop 전용 설정 및 도구 저장소

## 구조

```
goopick-claude/
├── settings/       # Claude Desktop 설정
├── prompts/        # 커스텀 프롬프트
├── mcp-servers/    # MCP 서버 설정
└── scripts/        # 자동화 스크립트
```

## 설정 위치

- **macOS**: `~/Library/Application Support/Claude/`
- **Windows**: `%APPDATA%\Claude\`

## 사용법

```bash
# 저장소 클론
git clone https://github.com/MadKangYu/goopick-claude.git

# 설정 동기화
./scripts/sync.sh
```
