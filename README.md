# 04_server

생성형 AI 활용 백엔드 데브코스 7기(aibe-7th) 4주차 Spring Boot 기초 및 웹 설정 실습 저장소입니다.

## 📂 구성 및 학습 자료

* **[40](40)**: 4주차 강의 교안 (PDF)
  * [401-1_Spring Boot 4와 Gradle.pdf](40/401-1_Spring%20Boot%204와%20Gradle.pdf): Spring Boot 스택, 내장 서버, Gradle 설정
  * [401-2_application-yml과 외부 설정.pdf](40/401-2_application-yml과%20외부%20설정.pdf): 외부화 설정, 우선순위, 프로파일, 값 주입, `.env` 설정
  * [401-3_Thymeleaf 기초.pdf](40/401-3_Thymeleaf%20기초.pdf): SSR 개념, Thymeleaf 표현식, XSS 방지, 조건 및 반복문
  * [402-1_Spring MVC와 Thymeleaf.pdf](40/402-1_Spring%20MVC와%20Thymeleaf.pdf): DispatcherServlet, 요청 바인딩, PRG 패턴, CRUD 라우팅, 폼 바인딩
  * [402-2_입력값 검증과 Bean Validation.pdf](40/402-2_입력값%20검증과%20Bean%20Validation.pdf): Bean Validation, @Valid, BindingResult, 오류 메시지 바인딩
  * [402-3_레이아웃과 프래그먼트.pdf](40/402-3_레이아웃과%20프래그먼트.pdf): th:fragment, th:replace, th:insert, Layout Dialect
  * [403_서버사이드 렌더링 예외 처리.pdf](40/403_서버사이드%20렌더링%20예외%20처리.pdf): BasicErrorController, 커스텀 오류 페이지, @ExceptionHandler, @ControllerAdvice
  * [404-1_파일 다루기.pdf](40/404-1_파일%20다루기.pdf): MultipartFile, 파일 업로드/저장/조회, FileStore 추상화
  * [404-2_객체 스토리지로 파일 저장하기.pdf](40/404-2_객체%20스토리지로%20파일%20저장하기.pdf): Supabase S3 호환 스토리지, Spring Cloud AWS, presigned URL
* **실습 프로젝트**:
  * [04_server-start](https://github.com/aibe-7th/04_server-start)
  * [04_server_thymeleaf](https://github.com/aibe-7th/04_server_thymeleaf)
  * [04_server_exception](https://github.com/aibe-7th/04_server_exception)
  * [04_server-storage](https://github.com/aibe-7th/04_server-storage)

## 🚀 시작하기

1. **실습 프로젝트 클론**
   ```bash
   git clone https://github.com/aibe-7th/04_server-start.git
   git clone https://github.com/aibe-7th/04_server_thymeleaf.git
   git clone https://github.com/aibe-7th/04_server_exception.git
   git clone https://github.com/aibe-7th/04_server-storage.git
   ```
2. 교안 자료([40](40))를 기반으로 환경 설정, 외부 설정, Thymeleaf, 파일 업로드/스토리지 실습 진행
