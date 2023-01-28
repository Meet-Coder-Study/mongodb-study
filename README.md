# MongoDB Study

- 몽고 DB 공부를 위한 저장소

> 개발, 운영, 관리, 확장, 성능 튜닝, 보안, 모니터링, 백업, 복구, 트러블슈팅 등등 많은 부분에 대해서 학습할 수 있지만 <br/>
> 실무 도입 시 개발자의 입장에서 사용방법, 유사한 기능을 제공하는 솔루션과의 차이에 대한 기준을 세울 수 있도록 학습하고 정리한다.

## 몽고 DB 의견 나누는 공간

- [몽고DB-완벽-가이드 - Discussions](https://github.com/orgs/Meet-Coder-Study/teams/db)
	- [몽고 DB 스터디 개요](https://github.com/orgs/Meet-Coder-Study/teams/db/discussions/1)
	- [1주차 목표](https://github.com/orgs/Meet-Coder-Study/teams/db/discussions/2)

## 스터디 정보

|      일정      |      시간       |                           스터디 도서                            | 목표                                                     |
|:------------:|:-------------:|:-----------------------------------------------------------:|:-------------------------------------------------------|
| 2023-01-14 ~ | 10:00 ~ 11:00 | [몽고 디비 완벽 가이드](http://www.yes24.com/Product/Goods/97980005) | 사용자 관점에 대한 내용을 우선 학습하기위해 <br/> 관리적인 측면의 챕터는 건너 뛰도록 한다. |

### 스터디 방식

- 매주 토요일 10시에 온라인으로 진행
- 스터디 진행을 위해 금요일 23:59까지 본인이 정리한 내용 또는 토론할 내용을 커멘트에 추가
  - 토른 주제는 해당 챕터와 직접 적인 연관 없는 내용도 환영
    - ex) 쿼리 실습 중에 접속 클라이언트를 무엇을 사용하였고, 이게 이런 기능이 있어서 편리하다.
    - ex) 이런 패턴 들은 우리에게 적용이 어려울 것 같고, 이런 패턴들은 적용하면 좋을거 같다.
  - 다른 사람의 코멘트에 적극적으로 질의도 환영
- 관리적인 측면이라고 생각하여 간단하게 보거나 Skip할 만한 챕터
  - **PART III 복제**
    - CHAPTER 10. 복제 셋 설정
    - CHAPTER 11 복제 셋 구성 요소
    - CHAPTER 12 애플리케이션에서 복제 셋 연결
    - CHAPTER 13 관리
  - **PART IV 샤딩**
    - CHAPTER 14 샤딩 소개
    - CHAPTER 15 샤딩 구성
    - CHAPTER 16 샤드 키 선정
    - CHAPTER 17 샤딩 관리
  - **PART V 애플리케이션 관리**
    - CHAPTER 19 몽고DB 보안 소개
  - **PART VI 서버 관리**
    - CHAPTER 23 백업
    - CHAPTER 24 몽고DB 배포

### 몽고 디비 완벽 가이드 - 목차

<details>
	<summary>PART I 몽고DB 시작</summary>
	<ul>
		<li>CHAPTER 1 몽고DB 소개</li>
		<li>CHAPTER 2 몽고DB 기본</li>
		<li>CHAPTER 3 도큐먼트 생성, 갱신, 삭제</li>
		<li>CHAPTER 4 쿼리</li>
	</ul>
</details>
<details>
	<summary>PART II 몽고DB 개발</summary>
	<ul>
		<li>CHAPTER 5 인덱싱</li>
		<li>CHAPTER 6 특수 인덱스와 컬렉션 유형</li>
		<li>CHAPTER 7 집계 프레임워크</li>
		<li>CHAPTER 8 트랜잭션</li>
		<li>CHAPTER 9 애플리케이션 설계</li>
	</ul>
</details>
<details>
	<summary>PART III 복제</summary>
	<ul>
		<li>CHAPTER 10 복제 셋 설정</li>
		<li>CHAPTER 11 복제 셋 구성 요소</li>
		<li>CHAPTER 12 애플리케이션에서 복제 셋 연결</li>
		<li>CHAPTER 13 관리</li>
	</ul>
</details>
<details>
	<summary>PART IV 샤딩</summary>
	<ul>
		<li>CHAPTER 14 샤딩 소개</li>
		<li>CHAPTER 15 샤딩 구성</li>
		<li>CHAPTER 16 샤드 키 선정</li>
		<li>CHAPTER 17 샤딩 관리</li>
	</ul>
</details>
<details>
	<summary>PART V 애플리케이션 관리</summary>
	<ul>
		<li>CHAPTER 18 애플리케이션 작업 확인</li>
		<li>CHAPTER 19 몽고DB 보안 소개</li>
		<li>CHAPTER 20 영속성</li>
	</ul>
</details>
<details>
	<summary>PART VI 서버 관리</summary>
	<ul>
		<li>CHAPTER 21 몽고DB 시작과 중지</li>
		<li>CHAPTER 22 몽고DB 모니터링</li>
		<li>CHAPTER 23 백업</li>
		<li>CHAPTER 24 몽고DB 배포</li>
	</ul>
</details>
<details>
	<summary>APPENDIX</summary>
	<ul>
		<li>A 몽고DB 설치</li>
		<li>B 몽고DB 내부</li>
	</ul>
</details>

## 진행 일정

|     일정     |        주제        | 핵심 내용                                                                                        | Discussions                                                                                         |
|:----------:|:----------------:|:---------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------|
| 2023-01-14 |        OT        | 몽고 DB 사용 여부 및 학습의 목표, 범위 설정, 일정 지정                                                           | [스터디 정리](https://github.com/orgs/Meet-Coder-Study/teams/db/discussions/1)                           |
| 2023-01-21 |        설날        | -                                                                                            |                                                                                                     |
| 2023-01-28 |  PART I 몽고DB 시작  | CHAPTER 1 몽고DB 소개 <br/> CHAPTER 2 몽고DB 기본 <br/> CHAPTER 3 도큐먼트 생성, 갱신, 삭제 <br/> CHAPTER 4 쿼리 | [CHAPTER 1 몽고DB 소개 ~ CHAPTER 4 쿼리](https://github.com/orgs/Meet-Coder-Study/teams/db/discussions/2) |
| 2023-02-04 | PART II 몽고DB 개발  | CHAPTER 5 인덱싱                                                                                | [CHAPTER 5 인덱싱](https://github.com/Meet-Coder-Study/mongodb-study/discussions/4)                    |
| 2023-02-11 |   PART III 복제    | -                                                                                            |                                                                                                     |
| 2023-02-18 | PART V 애플리케이션 관리 | -                                                                                            |                                                                                                     |
| 2023-02-25 |  PART VI 서버 관리   | -                                                                                            |                                                                                                     |
