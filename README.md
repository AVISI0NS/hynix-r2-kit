# hynix-r2-kit

SK하이닉스 AI 해커톤 2026 2차 예선용 개인 작업 키트. 파일 4개.

- `AGENTS.md` — Codex 작업 규칙 (핵심). 기준 설계, 병렬 세션(계산/산출물/검증), 산출물 규칙, 진행 기록 포함
- `NOTES.md` — 합의문·기준 표 / 세션 분담 / 가정 표 / 하지 못한 것 / 진행 기록
- `PROMPTS.md` — 프롬프트 (규칙 확인 → 파악 → 기준·계약 → 세션 A/B/C 구현 → 동결)
- `QUESTIONS.md` — 서술형 질문 34 (제출 전 10분용)

전제: 데이터 형식은 모른다(CSV라고 가정하지 않는다). 시험 환경은 git 커밋이 안 되므로 이력은 `NOTES.md` 4절에 남긴다. `SCHEMA.md`(결과 파일 계약)는 시험 중에 만든다.

대회 문제, 데이터, 결과물, 대화 기록은 포함하지 않으며 앞으로도 올리지 않는다. 2차 예선 결과 통지 전까지 공개 상태를 유지한다.

## 사용

과제 작업 폴더 루트에서:

```bash
git clone https://github.com/AVISI0NS/hynix-r2-kit.git .kit
cp .kit/AGENTS.md .kit/NOTES.md .
```

- 출제자가 준 AGENTS.md가 이미 있으면 덮어쓰지 말고 `cat .kit/AGENTS.md >> AGENTS.md`.
- PROMPTS.md, QUESTIONS.md는 복사하지 않고 `.kit/` 안에서 열어 두고 본다.
- Codex 세션은 새로 시작해야 AGENTS.md를 읽는다. 세션마다 0번 프롬프트로 확인.

참고: hamjoon2003/sk-hynix-2nd-harness (MIT), keepdev0919/hynix
