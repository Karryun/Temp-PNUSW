## 1. 프로젝트 소개
### 1.1. 개발배경 및 필요성
<img src="https://github.com/user-attachments/assets/6f229ad7-fb34-415b-9207-7b5d984e2349" alt="image" width="350" height="200"/>
<img src="https://github.com/user-attachments/assets/d49fccfb-c35e-4357-880e-4f2feb63585c" alt="090321454973395" width="250" height="200"/>

---
현재 부산대학교 인근 상권의 상황이 매우 심각한 상태입니다. 최근 조사에 따르면, 부산대학교 인근 상가의 공실률이 25.6%로 나타났으며, 이는 부산에서 가장 높은 공실률을 기록한 지역입니다. 이러한 상권의 악화는 학생들과 상인들 모두에게 막대한 영향을 미치고 있습니다. 특히, 상인들은 학생들이 더 자주 가게를 방문해주기를 희망하고 있으며, 이를 위해 학과나 학생들과의 제휴를 적극적으로 추진하고자 합니다. 이러한 협력 관계가 이루어진다면, 학생들은 보다 저렴한 가격에 가게를 이용할 수 있게 되며, 이는 상권 활성화에도 큰 도움이 될 것입니다.

또한 부산대학교와 관련된 제휴 정보들은 인스타그램, 에브리타임, 카카오톡, 웹사이트 등 다양한 플랫폼에 분산되어 제공되고 있습니다. 이로 인해 학생들이 필요한 제휴 정보를 효과적으로 찾는 것이 매우 어렵고, 정보 접근성 및 가독성 측면에서도 문제가 발생하고 있습니다. 특히, 인스타그램을 사용하지 않는 학생들에게는 정보 전달이 원활하지 않아, 제휴 혜택을 놓치는 경우가 빈번하게 발생하고 있습니다. 이러한 상황에서는 제휴의 실질적인 효과가 크게 감소할 수밖에 없기에 적절한 연결다리가 필요합니다.

<br/>

### 1.2. 개발목표 및 주요내용
**개발목표**

본 프로젝트의 개발 목표는 학생들에게 편리한 제휴 업체 정보 접근성을 제공함으로써 부산대학교 상권을 활성화하는 것입니다. 이 앱을 통해 학생, 학생회, 제휴 업체 간의 연결다리를 조성하여, 상권에 활력을 불어넣는 것을 목표로 하고 있습니다.

**주요 내용**

앱 개발의 주요 내용은 효율적이고 편리한 제휴 정보 전달 방식을 구현하는 것입니다. 이를 위해 네비게이션 바를 구성 요소별로 분류하여 다음과 같은 기능을 제공하고자 합니다:

  **a. 홈** 
> 카테고리별 맞춤 제휴 보기, 최신 제휴 공지 배너, 공지사항 확인 기능을 통해 사용자가 쉽게 정보를 얻을 수 있도록 합니다.

  **b. 디테일** 
>카테고리별 맞춤 제휴 보기와 사용자별 맞춤 제휴 정보를 제공하며, 크롤링을 통해 지속적으로 공지를 업데이트할 수 있습니다.

  **c. 맵** 
> 사용자가 내 주변 제휴 업체를 확인하고, 공고 클릭 시 디테일 페이지로 쉽게 이동할 수 있도록 하였습니다.

  **d. 마이페이지** 
>사용자 버전에서는 정보 수정, 리뷰 보기, 즐겨찾기, 알림 설정 기능을 제공하며, 관리자 버전에서는 공지 작성 및 관리를 할 수 있습니다.
<br/>

### 1.3. 세부내용
  1. 홈
      > 처음 회원가입 후 로그인을 하면 가장 처음으로 마주할 수 있는 화면입니다. 전체 제휴 정보를 볼 수 있는 버튼 1개, 카테고리별 7개 총 8개의 버튼이 먼저 보이고 그 밑에는 가장 최신으로 등록한 제휴 정보를 보여주는 화면이 나타납니다. 그리고 가장 밑에는 공지사항을 미리보기로 볼 수 있는 화면이 있습니다.
        

     - 카테고리 버튼

       > 전체보기 1개와 <술집, 카페, 문화, 음식점&식품, 헬스&뷰티, 교육, 의료&법> 카테고리 7개 총 8개의 버튼으로 이루어져 있고, 각 버튼을 클릭 시 그 카테고리에 맞는 디테일 화면으로 넘어가게 됩니다.
     - 최신 제휴 공지 배너 및 공지사항 미리보기
       > 가장 최신으로 등록된 제휴 공지를 간단하게 볼 수 있는 기능을 탑재하였습니다. 또한, 앱 관련 공지사항(버전 업데이트 등)을 미리보기로 볼 수 있는 기능도 구현하였습니다.
            

  2.    디테일
        > 더 자세한 제휴 정보를 볼 수 있는 화면이다. 각 카테고리 별로 확인을 할 수 있으며, 
    
  3.    맵
        > 플랫폼에 대한 피드백 및 사용자 간의 피드백이 가능하도록 하여, 전체적인 플랫폼 내의 서비스 질과 신뢰성을 향상시키기 위한 서비스이다. 유저 간의 리뷰 서비스, 활동 보고서, 문의하기(고객센터) 서비스 등이 포함된다.
        
        - 유저 간 피드백
          > 별점 기반 사용자 평가: 활동을 마친 후 서로에 대해 별점(1점~5점)을 부여한다. 별점은 활동에서의 상호 간의 태도, 시간 준수 여부 등을 기준으로 평가된다.
          > 활동 보고서 작성: 돌봄 활동을 하며 발생했던 사건이나, 특별한 경험, 개선사항 등을 바탕으로 활동 보고서를 작성할 수 있다.
       
        - 플랫폼 피드백
          > 이외에도 플랫폼 피드백을 위한 문의하기 서비스가 제공된다. 직접적으로 플랫폼에 대한 불편점이나, 요구 사항 등을 플랫폼 운영진 측에 전달할 수 있다. 

  4.   사용자 마이페이지
        > 활동을 무사히 마쳤음에 대한 인증, 회원 가입 시의 인증, 본인 활동 내역에 관한 인증을 포함하며, 학생증과 같은 신뢰 가능한 인증을 통해 서비스와 유저 간의 신뢰도를 높일 수 있다. 플랫폼 서비스라는 특성상, 대부분의 서비스가 신뢰를 바탕으로 이루어지고 있기 때문에 필수적인 서비스이다.
      
        - 활동에 대한 인증
            > 활동 시작 및 종료 시에 인증 절차가 진행된다. 돌봄 서비스가 성공적으로 개시, 종료되었음을 증명하기 위한 인증이며, 해당 인증에는 얼굴 인식 AI를 활용하여, 사진 한 장으로 시니어와 메이트가 돌봄 활동을 위해 대면으로 만났음을 인증할 수 있다.
        
        - 메이트의 가입 인증
            > 메이트의 경우, 대학생을 중심으로 하기에, 학교 학생증을 통해 인증을 할 수 있도록 한다. 이를 통해, 저택이나, 특정 장소로 시니어에 대한 돌봄 활동을 해야 하는 메이트 유저의 신뢰성을 확보하는데 도움을 준다. 
            
        - 활동 내역에 관한 인증
            > 메이트는 본인이 플랫폼 내에서 활동했던 기록에 대한 기록물을 인쇄하여 증빙 자료로 활용이 가능하다. 이를 활용하여 메이트가 향후 사회 활동 기여에 대한 증명이 가능할 것이며, 취업 혹은 여러 구직 활동 등에 사용할 수 있을 것으로 기대한다.
            
  5. 관리자 마이페이지
        > 플랫폼 진입 전 필수적으로 이수해야 하는 교육 서비스이다. 플랫폼 이용 시 행동 규범과 주의 사항을 이해하고, 미 준수 시 발생하는 문제점을 사전에 인지하도록 돕기 위해 설계되었다.
        
  6. 여러 부가 서비스
        > 플랫폼 이용에 편의성을 더하기 위한 채팅, 알림, 기존 복지 정보 제공 등의 부가 서비스가 존재한다. 기능과 직접적인 부분이기에 향후 기능 명세에 자세히 서술한다.

<br/>

### 1.4. 기존 서비스(상품) 대비 차별성
> 작성하세요.
<br/>

### 1.5. 사회적가치 도입 계획
> 작성하세요.
<br/>


### 2.상세설계
#### 2.1. 시스템 구성도
<img width="600px" alt="시스템 구성도" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/f0e7c7ed-deb1-47ee-8090-32f712fa2b23">
<br/>

#### 2.3. 사용기술
| 이름                  | 버전    |
|:---------------------:|:-------:|
| Python                | 3.8.0   |
| Django                | 3.2.9   |
| Django Rest Framework | 3.12.0  |
| Node.js               | 16.16.0 |
| Vue.js                | 2.5.13  |
<br/>


### 3. 개발결과
[코딩역량강화플랫폼 Online Judge](http://10.125.121.115:8080/)를 예시로 작성하였습니다.
#### 3.1. 전체시스템 흐름도
- 유저 플로우 차트
  > 코딩 역량강화 플랫폼의 회원가입 부분만 작성했습니다. <br/>
  > 사용자의 행동 흐름을 도식화하여 보여줍니다.
  <img width="400px" alt="유저 플로우 차트" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/c8de7c98-efd8-4f64-a39a-720faabccd78" />

- 테스크 플로우 차트
  > 코딩 역량강화 플랫폼의 로그인 부분만 작성했습니다. <br/>
  > 주요 테스크의 프로세스를 도식화하여 보여줍니다.
  <img width="400px" alt="테스크 플로우 차트" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/b83502a9-032d-4453-8687-428d54643610" />

- 시스템 플로우 차트
  > 코딩 역량강화 플랫폼의 로그인 부분만 작성했습니다. <br/>
  > 테스크의 흐름에 따른 데이터 처리를 도식화하여 보여줍니다.
  <img width="600px" alt="시스템 플로우 차트" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/1bfb66f0-446c-4450-8a81-a78bfe5ac9ce" />

  
- IA(Information Architecture)
  > 정보나 시스템의 구조를 도식화하여 보여줍니다. <br/>
  <img width="600px" alt="IA" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/07d842fe-fb73-4079-97a3-58b2495ff331" />

<br/>

#### 3.2. 기능설명
##### ` 메인 페이지 `
- 상단 배너
  - 3초에 마다 자동으로 내용이 넘어갑니다. <br/>
    ![상단 배너](https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/4640389f-dcaf-4b78-916e-188c8e9c6ee7)

- 공지사항
  - 최근 5개의 공지사항을 보여줍니다.
  - 발행된지 일주일이 안 된 공지사항은 new라는 mark표시를 해줍니다.
  - 공지사항 글을 클릭하면 해당 공지사항 게시글로 이동합니다.
  - 상단의 더보기 버튼을 클릭하면 공지사항 페이지로 이동합니다.<br/>
    <img width="600px" alt="공지사항" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/7c425946-ff06-4b32-8b18-4119cc86e308">

- 이번 주 보너스 문제
  - 이번 주의 보너스 점수를 주는 문제를 보여줍니다.
  - 문제를 클릭하면, 해당 문제의 게시글로 이동합니다. <br/>
    <img width="600px" alt="이번 주 보너스 문제" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/5c603984-8cf6-4524-84a6-5410bb6a8cbf">

- 실시간 랭킹
  - 상위 랭킹 10명의 유저를 보여줍니다.
  - 상단의 더보기 버튼을 클릭하면 전체 랭킹 페이지로 이동합니다.<br/>
    <img width="200px" alt="실시간 랭킹" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/8492e285-5423-4c00-bc46-400cbe733d35">
<br/>

##### ` 문제 페이지 `
- 문제 목록
  - 사용자가 설정한 한 번에 보여줄 문제 갯수 만큼 한 화면에 문제를 띄워줍니다.
  - 검색창에서 문제의 제목 및 번호로 문제를 검색할 수 있습니다.
  - 난이도, 영역, 카테고리 별로 문제를 볼 수 있습니다.
  - 상단의 shuffle 이모지를 클릭하면 랜덤으로 선택된 문제 푸는 페이지로 이동합니다.
  - 목록에서 문제를 클릭하면 해당 문제를 푸는 페이지로 이동합니다.
    ![문제 목록](https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/95afd0db-b5a7-4628-ac9c-164513a9e51b)
<br/>


#### 3.3. 기능명세서
<img width="200px" alt="실시간 랭킹" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/97ad3fea-f90a-437a-b611-3fb8cd24070e" />

|라벨|이름|상세|
|:---:|:----------------------------:|:---|
| S1  | 부산대학교 웹메일              | - 부산대 웹메일 형식인지 검증 <br/>- 중복되는 이메일인지 검증 |
| S2  | 부산대학교 웹메일 인증 코드 전송| - 클릭 시 인증 코드 메일로 전송 |
| S3  | 메일 인증 코드                 | - 인증 요청 버튼 클릭 후 활성화 <br/>- 유효시간 5분|
| S4  | 메일 인증 코드 확인            | - 인증코드 검증 |
| S5  | 닉네임                        | - 4 ~ 12자 영어, 숫자, '_' 가능 |
| S6  | 단과대학 선택                  | -부산대학교 단과대학 리스트 보여주기 |
| S7  | 학과 선택                     | - 단과대학 안의 학과 리스트 보여주기 |
| S8  | 비밀번호                      | - 입력 시 텍스트 보이지 않도록 •로 표현해주기 <br/>- 6자 이상 20자 이하, 영어와 숫자 조합 필수 |
| S9  | 비밀번호 확인                  | - 입력 시 텍스트 보이지 않도록 •로 표현해주기 <br/>- 비밀번호와 동일한 지 검증 |
| S10 | 회원가입 완료                  | - 비어 있는 입력 칸이 없는지 검증 <br/>-메일 인증 완료했는지 확인 <br/>-조건을 만족하면 회원가입 성공|
| S11 | 로그인                        | - 클릭 시 로그인 모달로 전환 |

<br/>

#### 3.4. 디렉토리 구조
```
├── build/                      # webpack 설정 파일
├── config/                     # 프로젝트 설정 파일
├── deplay/                     # 배포 설정 파일
├── src/                        # 소스 코드
│   ├── assets/                 # 이미지, 폰트 등의 정적 파일
│   ├── pages/                  # 화면에 나타나는 페이지
│   │   ├── page1/              # 페이지1
│   │   ├── page2/              # 페이지2
│   │   ├── components/         # 여러 페이지에서 공통적으로 사용되는 컴포넌트
│   ├── router/                 # 라우터
│   ├── store/                  # global state store
│   ├── styles/                 # 스타일
│   ├── utils/                  # 유틸리티
├── static/                     # 정적 파일
```
<br/>


### 4. 설치 및 사용 방법
**필요 패키지**
- 위의 사용 기술 참고

```bash
$ git clone https://github.com/test/test.git
$ cd test/frontend
$ npm i
$ export NODE_ENV="development" # windows: set NODE_ENV=development
$ npm run build:dll
$ export TARGET="http://localhost:8000"  # windows: set NODE_ENV=http://localhost:8000
$ npm run dev
```
<br/>


### 5. 소개 및 시연영상
[<img width="700px" alt="소개 및 시연영상" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/162132cd-9af5-4154-9b9a-41c96cf5e8fd" />](https://www.youtube.com/watch?v=EfEgTrm5_u4)

<br/>

### 6. 팀 소개
| 곽도연 | 김태란 | 서혜민 | 안소희 |
|:-------:|:-------:|:-------:|:-------:|
|<img width="100px" alt="곽도연" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/f5b5df2a-e174-437d-86b2-a5a23d9ee75d" /> | <img width="100px" alt="김태란" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/fe4e8910-4565-4f3f-9bd1-f135e74cb39d" /> | <img width="100px" alt="서혜민" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/675d8471-19b9-4abc-bf8a-be426989b318" /> |<img width="100px" alt="안소희" src="https://github.com/pnuswedu/SW-Hackathon-2024/assets/34933690/675d8471-19b9-4abc-bf8a-be426989b318" /> |
| gdy0210@pusan.ac.kr | taeran4767@pusan.ac.kr | gp4077@pusan.ac.kr | soheean1370@pusan.ac.kr |
| 백엔드 개발 <br/> UI/UX 디자인 | 아이디어 기획 <br/> 프론트엔드 개발 | 프론트엔드 개발 <br/> UI/UX 디자인 | 총괄 <br/> 백앤드 개발 |


<br/>


### 7. 해커톤 참여 후기
- 곽도연
  > 비록 개발을 아예 모르는 사람은 아니었지만 비전공자였기 때문에 초반에는 어려움이 많았습니다. 하지만 약 3개월의 시간 동안 팀원들과 같이 개발을 함으로써 프로그래밍 실력이 쌓여 개발에 흥미를 느끼게 된 좋은 계기가 된 것 같습니다.
- 김태란
  > 작성하세요.
- 서혜민
  > 작성하세요.
- 안소희
  > 작성하세요.
<br/>
