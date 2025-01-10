## SpringBoot Jpa 활용 MINI SHOP

- 김영한 SpringBoot JPA 학습 후 미니프로젝트

# 개발환경

- 프레임워크: Spring Boot 3.4.1 기반
- 언어 및 빌드: Java 21, Gradle 빌드 도구 사용
- 데이터베이스: H2 메모리 데이터베이스
- 애플리케이션 아키텍처:
  
  - Controller: API 요청 처리
  - Service: 비즈니스 로직 수행
  - Repository: 데이터베이스와의 상호작용
  - Domain-Driven Design (DDD) 기반 설계:
  - domain, repository, service, controller 등으로 나뉘어 관리.

# API

- 회원 관련
  
  1. 새로운 회원 등록 페이지를 제공 GET /members/new
  2. 회원 등록 처리 POST /members/new
  3. 모든 회원 목록 조회 GET /members

- 상품관련

  1. 새로운 상품 등록페이지 GET/items/new
  2. 상품 등록 처리 POST/items/new
  3. 상품 목록 조회 GET /items/{itemId}/edit
  4. 상품 정보 수정 처리 POST/items/{itemId}/edit

- 주문관련

  1. 주문페이지 제공 GET/order
  2. 주문 생성 GET/order
  3. 주문 목록 조회 GET/orders
  4. 주문 취소 처리 POST/orders/{orderId}/cancel



# 회원

- 회원가입
- 회원조회

# 상품

- 상품등록
- 상품수정
- 상품조회

# 주문

 - 주문등록
 - 주문취소
 - 주문내역 검색
 - 주문내역 조회
