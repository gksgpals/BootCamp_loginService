# WINK BootCamp — 게시판 서비스

국민대학교 웹 학술동아리 **WINK** 여름 부트캠프에서 만든 회원가입 · 로그인 기반 게시판 서비스입니다. (2025.08)

## 기능
- 회원가입 · 로그인 (`/auth`)
- 게시글 작성 · 조회 · 수정 · 삭제 (`/posts`, `/api/posts`)
- 댓글 작성 · 수정 · 삭제
- 게시글 좋아요 · 공유

## 구조
| 폴더 | 내용 |
|:---|:---|
| `Backend` | Spring Boot · Spring Data JPA · H2(인메모리 DB) 서버. 도메인: User · Post · Comment · Like · Share |
| `Frontend` | React 19 화면 (로그인/회원가입 폼, 게시글 작성 · 목록, 댓글) |
| `posting_project` | 위 Backend · Frontend와 같은 코드의 사본 |

## Tech
`Java` `Spring Boot` `Spring Data JPA` `H2` `React 19`

## 실행
```bash
# Backend (http://localhost:8080, H2 콘솔: /h2-console)
cd Backend && ./gradlew bootRun

# Frontend
cd Frontend && npm install && npm start
```
