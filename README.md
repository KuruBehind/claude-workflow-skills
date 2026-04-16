# claude-common-skills

Claude Code 공통 스킬셋. 기술 스택에 무관하게 어느 서비스 그룹에서도 재사용 가능한 범용 스킬 모음.

> 기술 스택 종속 스킬 (Flutter, Firebase 등)은 각 서비스 그룹 워크스페이스의 `skills/`에서 관리.

## 사용 방법

`~/Desktop/dev/` 아래 clone:

```bash
git clone https://github.com/KuruBehind/claude-common-skills
```

각 서비스 그룹 워크스페이스의 `CLAUDE.md`에서 상대경로로 참조:

```markdown
## 공통 스킬 (`../claude-common-skills/`)
- [브레인스토밍] `../claude-common-skills/brainstorming/SKILL.md`
- [플랜 작성] `../claude-common-skills/writing-plans/SKILL.md`
- [정책서 작성] `../claude-common-skills/writing-policy/SKILL.md`
- [서브에이전트] `../claude-common-skills/subagent-dev/SKILL.md`
```

## 스킬 목록

| 스킬 | 설명 |
|------|------|
| `brainstorming` | Step 0a 설계 수립 프로세스 |
| `writing-plans` | Step 0b 구현 플랜 작성 |
| `writing-policy` | Step 7 기획 정책서 + 개발 독스 작성 |
| `subagent-dev` | Step 2 태스크별 독립 에이전트 실행 |

## 업데이트

```bash
cd ~/Desktop/dev/claude-common-skills && git pull
```
