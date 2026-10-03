# cave

한국어 재테크·투자 유튜브 채널을 기획부터 댓글 관리까지 AI로 운영하기 위한 저장소입니다.

## 지금 들어 있는 것

| 위치 | 내용 |
|---|---|
| `channel/strategy.md` | 채널 콘셉트, 콘텐츠 기둥, 수익 구조, 업로드 전 규제·정책 체크리스트 |
| `channel/voice.md` | 말투 파일 초안. `[채워 주세요]` 칸을 직접 채워야 함 |
| `channel/plan-4weeks.md` | 첫 4주 업로드 계획 |
| `.claude/skills/yt-*` | 유튜브 운영 스킬 11개 ([youtube-agent-skill](https://github.com/Jakeschincariol/youtube-agent-skill), MIT) |
| `CLAUDE.md` | 이 저장소에서 스킬을 쓰는 규칙 |

이 저장소를 Claude Code로 열면 `/yt-script`, `/yt-plan` 같은 명령을 바로 쓸 수 있습니다.

## 로드맵

1. 채널 기획과 말투 파일 (완료, 말투 파일은 채널 주인이 채워야 함)
2. 영상 생성 파이프라인: 대본 → 음성 → 화면(표·차트) → 자막 → mp4
3. 썸네일 생성과 YouTube 업로드 (사람 승인 후 업로드)
4. 댓글 수집, 분류, 답글 초안 (사람 승인 후 게시)
5. 분석 데이터를 다음 기획에 반영
