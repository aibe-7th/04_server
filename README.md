# 04_server

생성형 AI 활용 백엔드 데브코스 7기(aibe-7th) 4주차 Spring Boot 기초 및 웹 설정 실습 저장소입니다.

## 📂 구성 및 학습 자료

* **[40](40)**: 4주차 강의 교안 (PDF - Part 1)
  * [401-1_Spring Boot 4와 Gradle.pdf](40/401-1_Spring%20Boot%204와%20Gradle.pdf): Spring Boot 스택, 내장 서버, Gradle 설정
  * [401-2_application-yml과 외부 설정.pdf](40/401-2_application-yml과%20외부%20설정.pdf): 외부화 설정, 우선순위, 프로파일, 값 주입, `.env` 설정
  * [401-3_Thymeleaf 기초.pdf](40/401-3_Thymeleaf%20기초.pdf): SSR 개념, Thymeleaf 표현식, XSS 방지, 조건 및 반복문
  * [402-1_Spring MVC와 Thymeleaf.pdf](40/402-1_Spring%20MVC와%20Thymeleaf.pdf): DispatcherServlet, 요청 바인딩, PRG 패턴, CRUD 라우팅, 폼 바인딩
  * [402-2_입력값 검증과 Bean Validation.pdf](40/402-2_입력값%20검증과%20Bean%20Validation.pdf): Bean Validation, @Valid, BindingResult, 오류 메시지 바인딩
  * [402-3_레이아웃과 프래그먼트.pdf](40/402-3_레이아웃과%20프래그먼트.pdf): th:fragment, th:replace, th:insert, Layout Dialect
  * [403_서버사이드 렌더링 예외 처리.pdf](40/403_서버사이드%20렌더링%20예외%20처리.pdf): BasicErrorController, 커스텀 오류 페이지, @ExceptionHandler, @ControllerAdvice
  * [404-1_파일 다루기.pdf](40/404-1_파일%20다루기.pdf): MultipartFile, 파일 업로드/저장/조회, FileStore 추상화
  * [404-2_객체 스토리지로 파일 저장하기.pdf](40/404-2_객체%20스토리지로%20파일%20저장하기.pdf): Supabase S3 호환 스토리지, Spring Cloud AWS, presigned URL
  * [405-1_PDF 문서로 RAG 구현하기.pdf](40/405-1_PDF%20문서로%20RAG%20구현하기.pdf): PDF 파싱 및 ETL 파이프라인, pgvector 기반 Vector Store, RAG 답변 생성
  * [405-2_이미지로 확장하는 멀티모달 RAG.pdf](40/405-2_이미지로%20확장하는%20멀티모달%20RAG.pdf): 멀티모달 캡셔닝/OCR, PgVectorStore 이중 구조, 크로스모달 검색
  * [405-3_프롬프트에서 이미지로.pdf](40/405-3_프롬프트에서%20이미지로.pdf): 이미지 생성(확산 모델), Cloudflare Workers AI 연동, RestClient 기반 커스텀 ImageModel 구현
* **[41](41)**: 4주차 강의 교안 (PDF - Part 2)
  * [411_Spring Security로 인증과 인가 적용하기.pdf](41/411_Spring%20Security로%20인증과%20인가%20적용하기.pdf): SecurityFilterChain, 인메모리 계정, 폼 로그인/세션, CSRF 방어, 예외 처리
  * [412-1_회원 관리와 DB 기반 인증 구현하기.pdf](41/412-1_회원%20관리와%20DB%20기반%20인증%20구현하기.pdf): JPA 회원 엔티티, PasswordEncoder, UserDetailsService 기반 DB 인증, 회원가입
  * [412-2_역할 기반 인가와 작성자 권한 검증.pdf](41/412-2_역할%20기반%20인가와%20작성자%20권한%20검증.pdf): @AuthenticationPrincipal, RBAC 인가 정책, 작성자 권한 검증 및 화면/서버 분기
  * [413_OAuth2 소셜 로그인 연동.pdf](41/413_OAuth2%20소셜%20로그인%20연동.pdf): OAuth2 Authorization Code Grant, oauth2Login, OAuth2UserService, 소셜 로그인 통합
* **[42](42)**: 4주차 강의 교안 (PDF - Part 3)
  * [421-1_REST API 기초.pdf](42/421-1_REST%20API%20기초.pdf): @RestController, ResponseEntity, DTO 바인딩 및 RESTful API 구현
  * [421-2_REST API 예외 처리와 문서화.pdf](42/421-2_REST%20API%20예외%20처리와%20문서화.pdf): @RestControllerAdvice, ProblemDetail, Springdoc OpenAPI/Swagger 기반 API 문서화
  * [422_CSR 연동과 CORS.pdf](42/422_CSR%20연동과%20CORS.pdf): SSR/CSR 구조 차이, SOP/CORS 동작 원리, Preflight, WebMvcConfigurer 기반 Spring Boot CORS 허용 설정 및 fetch 연동/트러블슈팅
  * [423_Spring Security와 REST API 인증·인가.pdf](42/423_Spring%20Security와%20REST%20API%20인증·인가.pdf): SecurityFilterChain 기반 선언형 보안, HTTP Basic 무상태 인증, Swagger UI 연동, CSRF 비활성화 및 CORS 처리, AuthenticationEntryPoint/AccessDeniedHandler를 통한 ProblemDetail 401·403 예외 응답 통일
* **실습 프로젝트**:
  * [04_server-start](https://github.com/aibe-7th/04_server-start)
  * [04_server_thymeleaf](https://github.com/aibe-7th/04_server_thymeleaf)
  * [04_server_exception](https://github.com/aibe-7th/04_server-exception)
  * [04_server-storage](https://github.com/aibe-7th/04_server-storage)
  * [04_server-ai-with-files](https://github.com/aibe-7th/04_server-ai-with-files)
  * [04_server-image-gen](https://github.com/aibe-7th/04_server-image-gen)
  * [04_server-sec](https://github.com/aibe-7th/04_server-sec)
  * [04_server_sec2](https://github.com/aibe-7th/04_server_sec2)
  * [04_server-rest](https://github.com/aibe-7th/04_server-rest)
  * [04_server-cors](https://github.com/aibe-7th/04_server-cors)

## 🚀 시작하기

1. **실습 프로젝트 클론**
   ```bash
   git clone https://github.com/aibe-7th/04_server-start.git
   git clone https://github.com/aibe-7th/04_server_thymeleaf.git
   git clone https://github.com/aibe-7th/04_server_exception.git
   git clone https://github.com/aibe-7th/04_server-storage.git
   git clone https://github.com/aibe-7th/04_server-ai-with-files.git
   git clone https://github.com/aibe-7th/04_server-image-gen.git
   git clone https://github.com/aibe-7th/04_server-sec.git
   git clone https://github.com/aibe-7th/04_server_sec2.git
   git clone https://github.com/aibe-7th/04_server-rest.git
   git clone https://github.com/aibe-7th/04_server-cors.git
   ```
2. 교안 자료([40](40), [41](41), [42](42))를 기반으로 환경 설정, 외부 설정, Thymeleaf, 파일 업로드/스토리지, RAG 및 이미지 생성, Spring Security 및 OAuth2 인증/인가, REST API 및 문서화, CORS 설정 및 REST API 보안 실습 진행
