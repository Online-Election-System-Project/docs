# UC - 선거와 투표 페이지 연동


#### 1. Related Requirements: 
REQ-11 (투표자는 공정한 선거를 위해서 선거당 한번만 투표할 수 있다.)


#### 2. Actor's Goal: 
선택한 선거에 대한 투표를 진행하고, 결과에 반영한다.

#### 3. Initiating actor: 
DB

#### 4. Flow of Events for Main Success Scenario:

-> 1. 본인인증을 마친 투표자가 실제 투표 페이지로 이동한다.
  
<- 2. 해당 선거에 등록된 각 후보자를 확인한 후 원하는 후보자를 선택한다.
  
<- 3a. 투표를 마친 투표자는 투표 완료 버튼을 누르고, 완료 메시지를 확인한 후 선거 목록 페이지로 돌아간다.
  
#### 5. Flow of Events for Extensions:

<- 3b. 아무 선택을 하지 않았을 경우, 투표가 종료되지 않는다.



