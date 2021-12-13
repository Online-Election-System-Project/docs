
# 산업체 핸즈온 프로젝트


# 주제

온라인 선거 시스템

# 서브그룹 


|   이름  |  학번 |  역할 분담 | 그룹 구분 |
|---------|------|------------|---------------|
|  강창훈 | 20170471|투표 시스템|Subgroup 1
|  김찬현 | 20172977|공보물 관리|Subgroup 2
|  박민기 | 20170807|투표 시스템|Subgroup 1
|  박준형 | 20176861|선거 관리|Subgroup 3
|  유호성 | 20172256|공보물 관리|Subgroup 2
|  허보성 | 20175969|선거 관리|Subgroup 3


# 스프린트 진행

1차 스프린트: 11/22~ 12/1 (미확정)

2차 스프린트: 12/2~


# 문서 링크


<a href="https://github.com/Online-Election-System-Project/docs/blob/main/Problem%20Statement.pdf">1. Problem Statement</a>

<a href="https://github.com/Online-Election-System-Project/docs/blob/main/Requirements%20Gathering.pdf">2. Requirement Gathering</a>

<a href="https://github.com/Online-Election-System-Project/docs/tree/main/UseCase">3. Use Case</a>

<a href="https://github.com/Online-Election-System-Project/docs/blob/main/Product%20Backlog.pdf">4. Product Backlog </a>

<a href="https://github.com/Online-Election-System-Project/docs/blob/main/구성원별 기여도">5. 구성원별 기여도 </a>



# 회의록
2021-11-14(일요일) 
- 주제선정, Requirements Gathering 작성

2021-11-22(월요일) 
- Problem Statement 정의 및 그에 따른 Requirement 반영 및 사이즈 수정

2021-11-23(화요일) 

- 대리투표, 개표조작이 가능하다는 문제점을 Problem Statement에 추가 & 그에 따른 Requirement 반영
 
2021-11-27(토요일) 
- 서브그룹 2에서 필요한 promotion(입후보등록) 테이블 스키마에 대한 공유 및 피드백
- Election(선거) 테이블 스키마에 대한 공유 및 피드백
 
2021-11-30(화요일) 
- 서브그룹1, 2의 기능이 유저가 구현되어야 진행에 수월할 것으로 판단. 
- 서브그룹3의 유저 관리 기능과 후보자 등록 요청 관리의 우선순위 서로 변경하기로 결정.
- promotion(입후보등록) 테이블 재구성
 
2021-12-03(금요일) 
- 서브그룹1의 기능인 투표를 위해 promotion 모델에 얻은 투표수 필드 생성을 서브그룹3에 요청
- 11/30에 바뀐 우선순위를 바탕으로, 서브그룹3 에서 유저 관리 기능(회원가입, 로그인, 회원 정보 수정, 탈퇴)구현 상황 공유 및 서브그룹 1,2에서 추가적으로 필요한 기능이 있는지 피드백
 
2021-12-07(화요일)
- 관리자, 후보자, 투표자 별로 가지는 권한을 논의 후에, 권한에 따른 페이지별 기능 결정.
 
2021-12-11(토요일) 
- 선거 결과를 보여주기 위해 공유되는(선거, 후보자) RDB 필드 재정리  
- 투표 완료시 어느 페이지로 연결이 되어야 하는지 논의
- 후보자가 보낸 등록 요청, 후보자 정보를 관리할 수 있도록, 후보자 관리 페이지 구성함.
 
2021-12-12(일요일)  
- 서브그룹2에서 사용할 수 있도록 선거와 후보자 모델을 통해 데이터가 연동된 실제 투표 기능에 관련된 내용 전달 
