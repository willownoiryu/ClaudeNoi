# ClaudeNoi — 석사 논문 프로젝트

> 논문 제목과 한 줄 요약을 여기에 작성하세요.

## 폴더 구조

```
.
├── manuscript/          # 논문 원고
│   └── chapters/        # 장별 원고 (01-서론, 02-이론적배경 ...)
├── references/          # 참고문헌
│   ├── references.bib   # 참고문헌 목록 (BibTeX, Zotero 등에서 내보내기)
│   └── papers/          # 논문 PDF (Git에는 올라가지 않음)
├── notes/
│   ├── meetings/        # 지도교수 미팅 기록
│   └── reading/         # 논문 읽기 노트
├── figures/             # 그림·표 원본
└── admin/               # 일정, 계획서, 심사 관련 문서
```

## 작업 규칙

- 파일 이름은 `YYYY-MM-DD-주제.md` 형식 (예: `2026-09-28-연구주제-논의.md`)
- 장별 원고는 번호를 붙여 순서 유지 (예: `01-introduction.md`)
- 의미 있는 단위로 자주 커밋 (예: "2장 선행연구 초안 작성")
- 논문 PDF는 용량과 저작권 문제로 Git에 올리지 않고 `references/papers/`에 로컬로만 보관

## 템플릿

- 미팅 기록: [`notes/meetings/_template.md`](notes/meetings/_template.md)
- 읽기 노트: [`notes/reading/_template.md`](notes/reading/_template.md)
- 일정: [`admin/timeline.md`](admin/timeline.md)
