# jpashop

## ๐งค ํ์ต ๊ฐ์
์ค์ ! ์คํ๋ง ๋ถํธ์ JPA ํ์ฉ1 - ์น ์ ํ๋ฆฌ์ผ์ด์ ๊ฐ๋ฐ

## Languages
<img src="https://img.shields.io/badge/Java-FFCA28"/>

## Technologies
<img src="https://img.shields.io/badge/H2 DB-FFCA28"/> <img src="https://img.shields.io/badge/JPA-orange"/> <img src="https://img.shields.io/badge/SpringBoot-blue"/> <img src="https://img.shields.io/badge/thymeleaf-green"/> 

## IDEA
<img src="https://img.shields.io/badge/IntelliJ IDEA-6A5FBB?style=flat-square&logo=IntelliJ IDEA&logoColor=white"/>

## ๐ํ๊ฒฝ ์ค์ 
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
//JUnit4 ์ถ๊ฐ
testImplementation("org.junit.vintage:junit-vintage-engine") {
exclude group: "org.hamcrest", module: "hamcrest-core"
}
```
## ๐ ๋ผ์ด๋ธ๋ฌ๋ฆฌ ์ดํด๋ณด๊ธฐ
> ์คํ๋ง ๋ถํธ ๋ผ์ด๋ธ๋ฌ๋ฆฌ 
* spring-boot-starter-web
   * spring-boot-starter-tomcat: ํฐ์บฃ (์น์๋ฒ)
   * spring-webmvc: ์คํ๋ง ์น MVC
* spring-boot-starter-thymeleaf: ํ์๋ฆฌํ ํํ๋ฆฟ ์์ง(View)
* spring-boot-starter-data-jpa
   * spring-boot-starter-aop
   * spring-boot-starter-jdbc
     *  HikariCP ์ปค๋ฅ์ ํ (๋ถํธ 2.0 ๊ธฐ๋ณธ)
   * hibernate + JPA: ํ์ด๋ฒ๋ค์ดํธ + JPA
   * spring-data-jpa: ์คํ๋ง ๋ฐ์ดํฐ JPA
* spring-boot-starter(๊ณตํต): ์คํ๋ง ๋ถํธ + ์คํ๋ง ์ฝ์ด + ๋ก๊น
   * spring-boot
     * spring-core
* spring-boot-starter-logging
     * logback, slf4j
     
> ํ์คํธ ๋ผ์ด๋ธ๋ฌ๋ฆฌ
* spring-boot-starter-test
   * junit: ํ์คํธ ํ๋ ์์ํฌ
   * mockito: ๋ชฉ ๋ผ์ด๋ธ๋ฌ๋ฆฌ
   * assertj: ํ์คํธ ์ฝ๋๋ฅผ ์ข ๋ ํธํ๊ฒ ์์ฑํ๊ฒ ๋์์ฃผ๋ ๋ผ์ด๋ธ๋ฌ๋ฆฌ
   * spring-test: ์คํ๋ง ํตํฉ ํ์คํธ ์ง์
   
> ํต์ฌ ๋ผ์ด๋ธ๋ฌ๋ฆฌ
* ์คํ๋ง MVC
* ์คํ๋ง ORM
* JPA, ํ์ด๋ฒ๋ค์ดํธ
* ์คํ๋ง ๋ฐ์ดํฐ JPA

> ๊ธฐํ ๋ผ์ด๋ธ๋ฌ๋ฆฌ 
* H2 ๋ฐ์ดํฐ๋ฒ ์ด์ค ํด๋ผ์ด์ธํธ
* ์ปค๋ฅ์ ํ: ๋ถํธ ๊ธฐ๋ณธ์ HikariCP
* WEB(thymeleaf)
* ๋ก๊น SLF4J & LogBack
* ํ์คํธ

## ๐์คํ ํ๋ฉด
<img width="80%" src="https://user-images.githubusercontent.com/46039671/178271865-ea38616c-2d45-4f4e-9436-f276e576666e.png"/>
<img width="80%" src="https://user-images.githubusercontent.com/46039671/178272698-1f5a4d48-b533-4a19-bea1-5c22566ee62a.png"/>

## ๐์ดํ
* ๊ฐ์๋ฅผ ๋ฃ๊ณ ๋์ SpringBoot์ JPA๋ฅผ ์ด๋ค์์ผ๋ก ์จ์ผ ํ๋์ง ์๊ฒ ๋์์ต๋๋ค. 
