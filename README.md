# jpashop

## 🧤 학습 강의
실전! 스프링 부트와 JPA 활용1 - 웹 애플리케이션 개발

## Languages
<img src="https://img.shields.io/badge/Java-FFCA28"/>

## Technologies
<img src="https://img.shields.io/badge/H2 DB-FFCA28"/> <img src="https://img.shields.io/badge/JPA-orange"/> <img src="https://img.shields.io/badge/SpringBoot-blue"/> <img src="https://img.shields.io/badge/thymeleaf-green"/> 

## 📝환경 설정
> gladle.build

```java
dependencies {
implementation 'org.springframework.boot:spring-boot-starter-data-jpa'
implementation 'org.springframework.boot:spring-boot-starter-validation'
implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'
implementation 'org.springframework.boot:spring-boot-starter-web'
compileOnly 'org.projectlombok:lombok'
runtimeOnly 'com.h2database:h2'
annotationProcessor 'org.projectlombok:lombok'
testImplementation 'org.springframework.boot:spring-boot-starter-test'
//JUnit4 추가
testImplementation("org.junit.vintage:junit-vintage-engine") {
exclude group: "org.hamcrest", module: "hamcrest-core"
}
```
## 📐 라이브러리 살펴보기
> 스프링 부트 라이브러리 
* spring-boot-starter-web
   * spring-boot-starter-tomcat: 톰캣 (웹서버)
   * spring-webmvc: 스프링 웹 MVC
* spring-boot-starter-thymeleaf: 타임리프 템플릿 엔진(View)
* spring-boot-starter-data-jpa
   * spring-boot-starter-aop
   * spring-boot-starter-jdbc
     *  HikariCP 커넥션 풀 (부트 2.0 기본)
   * hibernate + JPA: 하이버네이트 + JPA
   * spring-data-jpa: 스프링 데이터 JPA
* spring-boot-starter(공통): 스프링 부트 + 스프링 코어 + 로깅
   * spring-boot
     * spring-core
* spring-boot-starter-logging
     * logback, slf4j
     
> 테스트 라이브러리
* spring-boot-starter-test
   * junit: 테스트 프레임워크
   * mockito: 목 라이브러리
   * assertj: 테스트 코드를 좀 더 편하게 작성하게 도와주는 라이브러리
   * spring-test: 스프링 통합 테스트 지원
   
> 핵심 라이브러리
* 스프링 MVC
* 스프링 ORM
* JPA, 하이버네이트
* 스프링 데이터 JPA

> 기타 라이브러리 
* H2 데이터베이스 클라이언트
* 커넥션 풀: 부트 기본은 HikariCP
* WEB(thymeleaf)
* 로깅 SLF4J & LogBack
* 테스트

## 👀실행 화면
<img width="80%" src="https://user-images.githubusercontent.com/46039671/178271865-ea38616c-2d45-4f4e-9436-f276e576666e.png"/>
<img width="80%" src="https://user-images.githubusercontent.com/46039671/178272698-1f5a4d48-b533-4a19-bea1-5c22566ee62a.png"/>

## 🎈총평
* 강의를 듣고나서 SpringBoot와 JPA를 어떤식으로 써야 하는지 알게 되었습니다. 
  node.js와 react를 학습하고 나서 새로운 프로젝트를 만들때 주요하게 사용 하도록 하겠습니다.
