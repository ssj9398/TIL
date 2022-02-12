# 정리 및 회고


<details markdown="1">

<summary>2022년 2월 1일</summary>

- 알고리즘 </br>
  - 이코테 9문제 풀이, 프로그래머스 12문제 </br>
- 스프링 </br>
  - JPA 영속성, 엔티티, 매핑연관관계 복습
</details>

<details markdown="1">

<summary>2022년 2월 2일</summary>

- 알고리즘 </br>
  - 이코테 4문제 풀이, 프로그래머스 5문제 </br>
- 스프링 </br>
  - 엔티티 매핑
  - 연관관계 매핑 기초
  - 다양한 연관관계 매핑
  - 고급 매핑
  - 프록시와 연관관계 관리
  - 객체지향 쿼리 언어 - 기본문법
  - 객체지향 쿼리 언어 - 중급문법
</details>

<details markdown="1">

<summary>2022년 2월 3일</summary>

- 알고리즘 </br>
  - 이코테 9문제 풀이, 프로그래머스 12문제 </br>
- 트랜잭션, DOM공부 </br>
- 사이드 프로젝트 설계 </br>
</details>

<details markdown="1">

<summary>2022년 2월 4일</summary>

- 알고리즘 </br>
  - 이진탐색 강의, 프로그래머스 level1 2문제 </br>
- 트랜잭션, DOM공부 </br>
- 사이드 프로젝트 개발 시작 </br>
  - 엔티티 타입 수정, 단순 회원가입, 탈퇴 및 조회 기능 추가, validation gradle 추가 </br>
</details>

<details markdown="1">

<summary>2022년 2월 5일</summary>

- 알고리즘 </br>
  - 이진탐색 강의, 프로그래머스 level1 2문제 </br>
- 사이드 프로젝트 개발 시작 </br>
  - 찜리스트 테이블 추가, 연관관계 메소드 추가(댓글 등록), 회원정보 수정,회원가입 시간 추가, </br> 
  - springSecurity 초기설정, 엔티티 권한컬럼 추가, 구글, 네이버 로그인(Oauth2) 추가, Builder 추가 </br>
</details>

<details markdown="1">

<summary>2022년 2월 6일</summary>

- 알고리즘 </br>
  - 프로그래머스 level1 2문제 </br>
- 사이드 프로젝트 개발 시작 </br>
  - 내 작성글 조회, setter 제거,  n+1 문제 fetch join으로 해결 </br>
  - 마이페이지(사용자 엔티티) setter 제거 및 dto로 반환 </br>
  - 무분별한 setter 남용 방지 protected 추가, 내관심글 로직 추가 </br>
</details>

<details markdown="1">

<summary>2022년 2월 7일</summary>

- 알고리즘 </br>
  - 최단경로 강의, 프로그래머스 level1 2문제 </br>
- CORS 공부
- 사이드 프로젝트 개발 시작 </br>
  - 내 작성글 조회, setter 제거,  n+1 문제 fetch join으로 해결 </br>
  - 마이페이지(사용자 엔티티) setter 제거 및 dto로 반환 </br>
  - 무분별한 setter 남용 방지 protected 추가, 내관심글 로직 추가 </br>
</details>

<details markdown="1">

<summary>2022년 2월 8일</summary>

- 알고리즘 </br>
  - 최단경로 강의, 프로그래머스 level1 2문제 </br>
- 사이드 프로젝트 개발 시작 </br>
  - 내관심글 조회, 삭제 로직 추가, 관심게시물 삭제 추가, Role enum 타입으로 변경 </br>
</details>

<details markdown="1">

<summary>2022년 2월 9일</summary>

- 알고리즘 </br>
  - DP 강의, 프로그래머스 level1 2문제 </br>
- 사이드 프로젝트 개발 시작 </br>
  - 찜리스트 조회 삭제 수정, 리액트와의 연결을 위한 CORS 설정 </br>
  - 위시리스트 전체조회 추가, response 커스터마이징, MemberController 리팩토링 </br>
  - 예외처리 RuntimeException 커스터마이징 추가, 찜하기 부분 리팩토링 </br>

</details>

<details markdown="1">

<summary>2022년 2월 10일</summary>

- 알고리즘 </br>
  - 프로그래머스 level1 2문제 </br>
- 사이드 프로젝트 개발 시작 </br>
  - JSON, 라이브러리 추가, 카카오 로그인 추가, 관심글 이미 등록 된거 추가등록 방지를 위한 예외처리 </br>
</details>

<details markdown="1">

<summary>2022년 2월 11일</summary>

- 항해 과제 프로젝트 개발 시작 </br>
  - 게시글 전체 조회 완료
    - 제목, 작성자명, 작성 날짜를 조회하기
    - 작성 날짜 기준으로 내림차순 정렬하기 </br>
  - 게시글 작성
    - 제목, 작성자명, 작성 내용을 입력하기 </br>
  - 게시글 상세 조회
    - 제목, 작성자명, 작성 날짜, 작성 내용을 조회하기 </br>
  - 게시글 수정
    - 제목, 작성자명, 작성 내용 중 원하는 내용을 수정하기 </br>
  - 게시글 삭제
    - 원하는 게시물을 삭제하기 </br>
  - 게시글 등록 테스트 코드 완료 </br>
  - Docker, gitAction을 이용한 CI 구축 완료
    - 도커파일을 추가한다. (Dockerfile)
    ```
    # 1. node 설치
    FROM openjdk:8-jdk-alpine
    ARG JAR_FILE=build/libs/app.jar
    # 2. 소스 복사
    COPY ${JAR_FILE} app.jar
    ENTRYPOINT [ "java", "-jar","/app.jar" ]
    EXPOSE 80
    ```
    - gitAction으로 main으로 푸시하면 도커로 푸시하기위해 pipeline을 추가한다. </br>
    - (.github/workflows/ci-pipeline.yml)
    ```yml
    name: Java CI with Gradle

    on:
      push:
        branches: [ main ]
      pull_request:
        branches: [ main ]
    jobs:
      build:
        runs-on: ubuntu-latest
        steps:
        - uses: actions/checkout@v2
        - name: Set up JDK 11
          uses: actions/setup-java@v2
          with:
            java-version: '11'
            distribution: 'adopt'
        - name: Grant execute permission for gradlew
          run:  chmod +x gradlew
        - name: Build with Gradle
          run: ./gradlew build
        - name: Docker build
          run: |
            docker login -u ${{ secrets.DOCKER_USERNAME }} -p ${{ secrets.PASSWORD }}
            docker build -t spring-boot .
            docker tag spring-boot alisyabob/spring-boot:${GITHUB_SHA::7}
            docker push alisyabob/spring-boot:${GITHUB_SHA::7}
    ```
    
    </br>

    - 편의를 위해build.gradle 수정해주기
    ```java
    jar {
        enabled = false
    }

    bootJar{ archivesBaseName = 'app'
        archiveFileName = 'app.jar'
        archiveVersion = "0.0.0"
    }
    ```
    - 수동으로 도커 허브에 올리는 방법
    ```
    docker build -t spring-boot .
    docker run -d -p 80:80 spring-boot
    docker tag spring-boot 계정/spring-boot
    docker push 계정/spring-boot
    ```


</details>