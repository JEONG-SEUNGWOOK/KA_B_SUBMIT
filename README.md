# README  

## Framework, etc..
- Spring Boot 2.1.6  
- Gradle  
- DBMS : H2  
- thymeleaf
- JPA

## Description  
1. 프로그램 실행 
>java -jar kakaobank.jar

2. 접속url 
>localhost:8080

3. 프로그램 실행시, 테이블 및 사용자 계정 자동생성
>ID : admin / PW : 1234

4. 비밀번호는 **bCrytp** 라이브러리를 사용하여 암호화
5. 인기검색어는 첫 검색 후, 히스토리 생성되며 활성화
6. 장소검색은 서버페이징을 사용하여 구현

## 오픈소스 및 라이브러리
1. kendo UI : 검색결과, 페이지네이션, 버튼 구현
2. semantic UI : UI디자인 및 인기검색어 창 구현
3. bootstrap : 1,2 번 라이브러리를 위한 베이스 라이브러리
4. okhttp3 : http request 요청 
5. bCrypt : 비밀번호 암호화
6. font awesome : icon 저장소 

## 화면설계서
https://ovenapp.io/project/LCUP8pFwrjzx8jc49jDNq3cignYpExV9#CJAMK