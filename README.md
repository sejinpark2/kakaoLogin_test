# kakaoLogin

## ※ 개발환경
IDE: IntelliJ IDEA Community   
Gradle - Groovy, Java 17
Jar 11   
Spring Boot 2.7.6   
JDK 11   
mysql 8.0.35   
Lombok   
Spring Web   
Spring Data JPA   

---
|링크|기능| |
|:--:|:--:|:--:|
|/join|회원가입|정보 저장|
|/login|로그인|저장된 정보로 토큰발급|
|/check|이메일 중복 확인|Find Email|
|/oauth/kakao|카카오 로그인|카카오 기반 로그인|


## ※ 회원가입 및 로그인 주요기능    
### 일반 회원 
1. 회원가입(/join) <br>
  \- 이메일, 비밀번호, 이름, 전화번호

2. 이메일 중복 확인(/check)

3. 로그인(/login)

4. 로그아웃(/logout) <br>

### 카카오톡 회원
1. 카카오톡로 회원가입 및 로그인(/oauth/kakao)

2. 카카오톡으로 로그아웃(/kakao/logout) <br>


