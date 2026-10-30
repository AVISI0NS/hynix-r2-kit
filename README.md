# hynix-r2-kit

SK하이닉스 AI 해커톤 2026 2차 예선용 개인 작업 키트.

- Codex 작업 규칙(`AGENTS.md`), 과제 계약 템플릿(`TASK.md`), 결정 기록 템플릿(`DECISIONS.md`), 단계별 프롬프트 대본(`PROMPTS.md`)만 담는다.
- 대회 문제, 데이터, 결과물, 대화 기록은 포함하지 않으며 앞으로도 올리지 않는다.
- 2차 예선 결과 통지 전까지 공개 상태를 유지한다.

## 사용

과제 작업 폴더 루트에서:

```bash
git clone https://github.com/AVISI0NS/hynix-r2-kit.git .kit
cp .kit/AGENTS.md .kit/TASK.md .kit/DECISIONS.md .
# 출제자가 준 AGENTS.md가 이미 있으면 덮어쓰지 말고: cat .kit/AGENTS.md >> AGENTS.md
echo ".kit/" >> .git/info/exclude
```

이미 열려 있던 Codex 세션은 재시작해야 AGENTS.md를 읽는다.

## 참고

- hamjoon2003/sk-hynix-2nd-harness (MIT) — 절대 규칙, 증거 규칙, TASK/DECISIONS 구조
- keepdev0919/hynix — 커밋 규칙, 중단 조건, 환경 메모
