# ClaudeNoi — 석사 논문 프로젝트

> 논문 제목과 한 줄 요약을 여기에 작성하세요.

## 폴더 구조

```
.
├── manuscript/          # 논문 원고 (LaTeX)
│   ├── main.tex         # 메인 파일 — 논문 제목·이름 등 기본 정보
│   ├── preamble.tex     # 패키지·서식 설정 (여백, 줄 간격, 참고문헌 스타일)
│   ├── frontmatter/     # 표지, 국문·영문 초록
│   ├── chapters/        # 본문 1~5장
│   └── backmatter/      # 부록, 감사의 글
├── references/          # 참고문헌
│   ├── references.bib   # 참고문헌 목록 (BibTeX, Zotero 등에서 내보내기)
│   └── papers/          # 논문 PDF (Git에는 올라가지 않음)
├── notes/
│   ├── meetings/        # 지도교수 미팅 기록
│   └── reading/         # 논문 읽기 노트
├── figures/             # 그림·표 원본
└── admin/               # 일정, 계획서, 심사 관련 문서
```

## 논문 컴파일하기

XeLaTeX + Biber로 컴파일합니다. PDF는 `manuscript/build/main.pdf`에 생성됩니다 (Git에는 올라가지 않음).

**Overleaf**
1. 이 레포를 Overleaf로 가져오기 — New Project → Import from GitHub (GitHub 연동은 Overleaf 유료 기능이에요. 무료라면 `manuscript/`, `references/`, `figures/` 폴더를 zip으로 묶어 Upload Project)
2. Menu → Main document: `manuscript/main.tex`, Compiler: `XeLaTeX`

**로컬** (TeX Live 설치 후)
```bash
cd manuscript
latexmk          # 컴파일
latexmk -pvc     # 저장할 때마다 자동으로 다시 컴파일
latexmk -c       # 임시 파일 정리
```

**처음 해야 할 일**
- `main.tex` 위쪽의 제목, 이름, 학과, 제출일 수정
- `preamble.tex`의 여백·줄 간격·참고문헌 스타일을 학교 규정에 맞추기
- `references/references.bib`의 예시 항목을 실제 참고문헌으로 교체

## 작업 규칙

- 파일 이름은 `YYYY-MM-DD-주제.md` 형식 (예: `2026-09-28-연구주제-논의.md`)
- 장별 원고는 번호를 붙여 순서 유지 (예: `chapters/01-introduction.tex`)
- 의미 있는 단위로 자주 커밋 (예: "2장 선행연구 초안 작성")
- 논문 PDF는 용량과 저작권 문제로 Git에 올리지 않고 `references/papers/`에 로컬로만 보관

## 템플릿

- 미팅 기록: [`notes/meetings/_template.md`](notes/meetings/_template.md)
- 읽기 노트: [`notes/reading/_template.md`](notes/reading/_template.md)
- 연구 주제 정리: [`notes/topic.md`](notes/topic.md)
- 일정: [`admin/timeline.md`](admin/timeline.md)
