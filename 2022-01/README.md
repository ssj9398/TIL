# 정리 및 회고
- 1월 18일 드디어 쉬운문제이긴 하지만 알고리즘 문제가 하나둘 풀리기 시작했다.
  - 파이썬을 처음 접하는건 아니었지만 쓰던 문법만 써왔던 나로선 이전에 알고 있던 
  - c, java, javascript 와 헷갈리면서 조금 힘들었다. (기존에 알고 있던 언어와도 조금 혼동)
- 1월 23일 대학교 졸업만 하면 이제 발표할 일이 없을거 같았는데 이번 항해99라는 부트캠프를 하면서
  - 그래프(dfs) 부분집합 발표를 진행하게 되었는데 너무 긴장되서 많이 못한 거 같다.
  - 어떻게 극복할지 녹화한 영상을 봐야겠다. 

<details markdown="1">

<summary>2022년 1월 14일</summary>


- 패캠 알고리즘 </br>
  - 자료구조와 알고리즘 </br>
  - 배열 </br>
  - 큐 </br>
  - 스택 </br>
  - 링크드리스트 </br>
- 파이썬 알고리즘 인터뷰 책 </br>
  - 4장 빅오, 자료형 </br>
  - 5장 리스트, 딕셔너리 </br>
  - 6장 문자열조작 </br>
  - 7장 배열 </br>
- 스프링 핵심 원리 (인프런 - 김영한) </br>
  - 싱글톤 </br>

</details>

<details markdown="1">

<summary>2022년 1월 16일</summary>

- 도커 </br>
  - 도커 기본 명령어 </br>
  - 도커 컴포즈 기본 </br>
- 알고리즘 </br>
  - [파이썬 기본문법](https://alisyabob.tistory.com/325) </br>
  - 백준 기초문제 </br>

</details>

<details markdown="1">

<summary>2022년 1월 17일</summary>

- 도커 </br>
  - 도커 이미지 만들기(nginx, nodejs) </br>
  - 도커 이미지 관리</br>
  - 도커 이미지 배포</br>
- 알고리즘 </br>
  - 백준 기초문제 </br>
  - 파이썬 알고리즘 인터뷰 </br>

</details>

<details markdown="1">

<summary>2022년 1월 18일</summary>

- 도커 </br>
  - Nginx를 이용한 정적 페이지 서버 만들기 </br>
- 알고리즘 </br>
  - 백준 기초문제 </br>
  - 파이썬 알고리즘 인터뷰 책 </br>
    - 스택, 큐, 연결리스트 </br>

</details>

<details markdown="1">

<summary>2022년 1월 19일</summary>

- 알고리즘 </br>
  - 백준 기초문제 </br>
  - 파이썬 알고리즘 인터뷰 책 </br>
    - 스택, 데크, 큐 해시 테이블 </br>
  - 백준 기초 문제  </br>

</details>

<details markdown="1">

<summary>2022년 1월 20일</summary>

- 도커 </br>
  - ghost 블로그 컨테이너 생성 </br>
  - 방명록 배포해보기 </br>
  - 투표 앱 생성해보기 </br>
  - 실시간 채팅앱 생성 </br>
- 알고리즘 </br>
  - 백준 기초문제 </br>
  - 파이썬 알고리즘 인터뷰 책 </br>
    - 배열, 연결리스트, 스택 </br>

</details>

<details markdown="1">

<summary>2022년 1월 21일</summary>

- 알고리즘 </br>
  - 백준 기초문제 </br>
  - 파이썬 알고리즘 인터뷰 책 </br>
    - 해시 테이블, 그래프 </br>
  - 패스트캠퍼스 강의 </br>
    - bfs, dfs </br>

</details>

<details markdown="1">

<summary>2022년 1월 22일</summary>

- 도커 </br>
  - 도커 강의 복습 </br>
- 알고리즘
  - 파이썬 알고리즘 인터뷰 책 </br>
    - 데크, 큐, 그래프 </br>
  - 패스트캠퍼스 강의 </br>
    - 트리, 해쉬테이블 </br>
- 그래프(dfs) 부분집합 발표
```python
  - from typing import List

class test:
    def subsets(self, nums: List[int]) -> List[int]:

        # 결과를 받을 빈배열 생성
        res = []

        def dfs(index, path):
            res.append(path)

            print("res", res)
            for i in range(index, len(nums)):
                print("-------------------------------")
                print("iiii",i)
                dfs(i + 1, path + [nums[i]])
                print("path", path, "nums", [nums[i]])

        dfs(0, [])
        return res

test = test()
test.subsets([1, 2, 3])
```

</details>

<details markdown="1">

<summary>2022년 1월 24일</summary>

- 알고리즘 </br>
  - 백준 기초문제 </br>
  - 패스트캠퍼스 강의 </br>
    - 백트래킹 </br>
- 스프링
  - 싱글톤 컨테이너
  - 컴포넌트 스캔 

</details>

<details markdown="1">

<summary>2022년 1월 25일</summary>

- 알고리즘 </br>
  - 백준 기초문제, 프로그래머스 LEVEL1 </br>
  - 패스트캠퍼스 강의 </br>
    - 트리 </br>
- 스프링
  - 의존관계 자동 주입
  - 빈 생명주기
  - 빈 스코프

</details>

</br>
