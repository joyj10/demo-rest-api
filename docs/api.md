# 온라인 서점 - API

## 온라인 서점 URI
### 책 등록
- POST /book

### 책 목록 조회
- GET /books

### 책 상세 조회
- GET /books/{bookId}

### 저자별 책 조회
- GET /books?author={authorName}

### 책 리뷰 조회
- GET /books/{bookId}/reviews

## 테이블
- book
- author
- review
