# agent-playground

AI 관련 기술들을 연구하고, 테스트하고, 실무에 적용하기 위한 개인 실험 공간입니다.

## 목적

- AI 에이전트 패턴 및 워크플로우 연구
- LLM API (Claude, OpenAI 등) 활용 실험
- MCP(Model Context Protocol) 서버 및 도구 통합
- 프롬프트 엔지니어링 및 최적화 기법 탐구
- 실무 적용 가능한 AI 기술 검증

## 구조

```
agent-playground/
├── .claude/              # Claude Code 설정 및 가이드라인
│   ├── CLAUDE.md         # 코딩 행동 지침
│   ├── EXAMPLES.md       # 사용 예시
│   ├── docs/             # 문서
│   └── skills/           # 커스텀 스킬
└── README.md
```

> 실험 주제별 디렉토리는 탐구 영역이 확장되면서 추가될 예정입니다.

## 탐구 영역

| 영역 | 설명 |
|------|------|
| Agents | 자율 에이전트 설계, 도구 사용, 멀티 에이전트 협업 |
| Prompting | 시스템 프롬프트, few-shot, chain-of-thought, 프롬프트 캐싱 |
| MCP | MCP 서버 구현 및 Claude Code와의 통합 |
| Workflows | 실무에 적용 가능한 AI 자동화 파이프라인 |
| Evals | 모델 출력 평가 및 품질 측정 |

## 사용 모델

기본적으로 Anthropic Claude 모델을 중심으로 실험합니다.

- **Claude Opus 4.7** (`claude-opus-4-7`) — 복잡한 추론, 에이전트 작업
- **Claude Sonnet 4.6** (`claude-sonnet-4-6`) — 범용, 균형 잡힌 성능
- **Claude Haiku 4.5** (`claude-haiku-4-5-20251001`) — 빠른 응답, 경량 작업

## 개발 환경

- **OS**: Windows 11
- **Shell**: PowerShell / Bash
- **IDE**: VS Code + Claude Code 확장
- **CLI**: Claude Code (`claude`)
