# 📚 개발 서적 아카이브

개발 서적을 읽고 **실무 관점**으로 재정리한 노트를 모읍니다.  
목표는 **재사용 가능한 지식 단위**(패턴, 스멜, 트레이드오프, 보안 체크리스트)를 축적하는 것.

## 🚀 빠른 시작
- 전체 목차: [SUMMARY.md](./SUMMARY.md)
- 주제별 색인: [tags/](./tags/)
- 예제 코드 스니펫: [snippets/](./snippets/)

## 🧭 정리 원칙
1. **근거 우선**: 페이지·절 번호/인용과 함께 요약 (가능하면 원문 키워드 유지).
2. **개념→적용→한계**: 정의→실전 적용 예→트레이드오프/안티패턴.
3. **객체지향/클린코드 렌즈**: 책임 분리, 응집도/결합도, 인터페이스 중심 설계로 재서술.
4. **보안 관점 병기**: 입력 검증, 인증/인가, 데이터 처리, 로깅·감사 항목 체크.
5. **재현 가능한 예제**: 모든 코드에 실행 방법/테스트 명시.

## 📖 진행 현황
| 책 | 저자 | 판/연도 | 상태 | 노트 |
|---|---|---:|:---:|---|
| Clean Code | Robert C. Martin | 2008 | 진행중 | [폴더](./book/clean-code_(2010)_martin/) |
| Effective Java 3/E | Joshua Bloch | 2018 | 완료(요약중) | [폴더](./book/effective-java_3e_(2018)_bloch/) |

## 🏷️ 태그 정책
- 기술: `#java`, `#spring`, `#JPA`, `#concurrency`, `#security`
- 원칙/패턴: `#oop`, `#solid`, `#refactoring`, `#design-patterns`
- 데이터/성능: `#sql`, `#indexing`, `#caching`, `#profiling`
- 포맷: 소문자-하이픈, 문서 상단 YAML에 `tags` 배열로 명시

## 📦 폴더 규칙
- `book/<제목slug>_(연도)_(저자)/notes/NN-<topic>.md`
- 챕터 번호를 접두어로 → 정렬·진행도 파악 쉬움

## 🔎 검색 최적화
- 문서 상단 YAML Front-matter + 본문에 **키워드 표준화 용어집** 링크
- 인용: `"원문 키워드"(p.42)` 형식으로 반복 가능하게

## ✅ CI/Lint
- PR 시 Markdown 검사(깨진 링크/heading 규칙/표 스타일)
- 워크플로우: [./.github/workflows/markdown-ci.yml](./.github/workflows/markdown-ci.yml)

## 📝 라이선스/인용
- 이 레포의 서술·예제 코드는 MIT.
- 원저작권은 각 도서/출판사에 귀속. 인용은 **짧은 발췌 + 출처/페이지** 원칙.
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
