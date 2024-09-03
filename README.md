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

<br/>

2. 디테일
> 더 자세한 제휴 정보를 볼 수 있는 화면입니다. 각 카테고리 별로 확인을 할 수 있으며, 현재 진행 중인 제휴 공고만 확인할 수도 있습니다. 또한 제휴 미리보기 클릭 시 상세페이지가 나와 더 자세한 제휴 공고를 볼 수 있습니다. 세부 제휴 공고에는 제휴 내용 및 사용자의 리뷰 확인도 가능합니다.


 - 카테고리 버튼 및 진행 중인 제휴 확인
  > 홈 화면과 비슷한 기능이지만 제휴 정보 미리보기를 가로로 스크롤하여 바로 볼 수 있습니다. 또한, 진행 중인 제휴만 열람이 가능해 효율적인 정보 확인이 가능합니다.
 - 세부 제휴 정보 및 리뷰 열람
  > 제휴 정보 미리보기를 누르면 세부 제휴 정보가 뜨게 됩니다. 제휴 업체명과 제휴 기간이 맨 위에 나오고 내용이 밑에 나옵니다. 스크롤하여 맨 아래로 내리면 이 제휴를 사용한 사람들의 리뷰 및 평점도 확인할 수 있습니다.


<br/>
    
3. 맵
> 제휴 가게가 어디에 위치해 있는 지를 지도로 한 눈에 볼 수 있는 화면입니다.
        
- 제휴 등록 가게 마커 표시(+ 내 위치 확인)
 > 이 앱에 등록된 모든 등록 가게를 확인할 수 있습니다. 그리고 내 위치를 확인할 수 있어 제휴 가게가 어느 위치에 있는 지를 대략적으로 파악할 수 있습니다.

<br/>
       
4. 사용자 마이페이지
> 일반 사용자가 로그인을 하였을 때 볼 수 있는 화면입니다. 닉네임과 전공이 위에 보여지며, 내 정보 수정 및 내가 작성한 리뷰 목록을 확인할 수 있습니다.
      
- 내 정보 수정
  > 회원가입 시 등록한 닉네임과 전공을 바꾸고 싶을 경우에 이 기능을 통해서 수정이 가능합니다.
        
- 내가 작성한 리뷰 확인
  > 사용자가 작성한 리뷰에 대한 내용과 평점을 전체적으로 확인할 수 있게 합니다.

<br/>

5. 관리자 마이페이지
   
> 관리자 인증을 받은 계정이 로그인을 했을 때 볼 수 있는 화면입니다. 제휴공지 및 앱 관련 공지사항을 작성 및 관리할 수 있습니다.


<br/>

### 1.4. 기존 서비스(상품) 대비 차별성
기존의 제휴 매장 홍보 방식은 커뮤니티 앱(카카오톡, 인스타그램) 등을 통한 단방향적인 정보 전달에 그치고 있으며, 이는 접근성이 낮고 사용자가 정보를 빠르게 잊어버리기 쉽다는 한계가 있습니다. 또한, 부산대 총학생회 제휴 웹사이트의 경우 접근성이 낮아 많은 학생들이 이를 활용하지 못하고 있으며, 총학생회와 단과대 제휴 공지가 여러 곳에 흩어져 있어 정보의 일관성과 통합성이 부족합니다.

이에 반해, 우리의 앱은 제휴 정보를 한눈에 알기 쉽게 정리하여 제공함으로써 정보 접근성을 크게 향상시킵니다. 또한, 기존의 단방향적인 정보 전달 방식을 개선하여 학생들과 상인 간의 양방향 정보 공유를 가능하게 합니다. 이를 통해, 학생들은 필요한 정보를 빠르고 쉽게 얻을 수 있으며, 상인들도 학생들의 피드백을 직접 받아 볼 수 있어 상호작용이 활발해질 것입니다. 

이와 같은 정보의 통합성과 양방향 소통 기능은 기존 서비스와의 가장 큰 차별점이며, 이를 통해 사용자 경험을 대폭 개선할 수 있습니다.


<br/>

### 1.5. 사회적가치 도입 계획
WithPNU 프로젝트는 부산대학교 인근 상권의 회복과 활성화를 목표로 합니다. 이를 위해 우리는 학생, 학생회, 제휴 업체 간의 상호작용을 촉진하는 플랫폼을 개발하고, 이를 통해 지역 경제와 공동체에 긍정적인 영향을 미치고자 합니다.

우선, 학생들에게는 다양한 제휴 정보를 한눈에 쉽게 접근할 수 있도록 함으로써, 이용 가능한 혜택을 최대화할 수 있는 기회를 제공합니다. 이를 통해 학생들이 경제적으로 부담을 덜면서 지역 상권을 적극적으로 이용하게 됩니다.

또한, 상인들에게는 학생들과의 직접적인 소통 채널을 제공하여 제휴 참여를 활성화하고, 학생들의 피드백을 반영할 수 있는 기회를 줍니다. 이는 상인들이 학생들의 요구에 맞춘 상품과 서비스를 제공하는 데 도움이 되며, 결과적으로 지역 경제의 활력을 증진시키는 데 기여할 것입니다.

추가로, 앱을 통해 제공되는 다양한 기능들은 단방향적인 정보 전달에서 벗어나 양방향 소통을 가능하게 하며, 이는 지역 사회 구성원 간의 긴밀한 협력을 촉진합니다. 이러한 접근은 단순한 상거래를 넘어 지역 사회의 지속 가능한 발전을 도모하는 데 중점을 두고 있습니다.

따라서 WithPNU는 단순한 정보 제공 앱을 넘어서, 지역 사회의 경제적 활성화와 공동체 강화라는 사회적 가치를 실현하는 중요한 도구로 자리잡을 것입니다.
<br/>


## 2.상세설계
### 2.1. 시스템 구성도
<img src="https://github.com/user-attachments/assets/b2c14197-06e8-47c6-a282-b18a82873bd4" alt="image" width="600" height="300"/>


<br/>

### 2.2. 사용기술
| 이름                  | 버전    |
|:---------------------:|:-------:|
| Kotlin                | 1.9.0   |
| Firebase Database     | 20.0.5  |
| Firebase Storage      | 20.0.1  |
<br/>


## 3. 개발결과
[코딩역량강화플랫폼 Online Judge](http://10.125.121.115:8080/)를 예시로 작성하였습니다.
### 3.1. 전체시스템 흐름도

#### 유저 플로우 차트

  ①. 로그인 및 회원가입 (+비번 찾기)

![image](https://github.com/user-attachments/assets/2d94a459-5501-4293-bb67-87f03942af29)

  ②. 홈 화면

![image](https://github.com/user-attachments/assets/e783e179-58fb-450c-b25c-77f2a2e48efc)


  ③. 디테일 화면

![image](https://github.com/user-attachments/assets/a0873c58-582d-43ac-a1c8-eec2fb789e8c)

  ④. 맵 화면

![image](https://github.com/user-attachments/assets/7da64803-6276-435e-bd4f-6bceebed43e8)

  ⑤. 사용자 마이페이지 화면

![image](https://github.com/user-attachments/assets/dabc61e3-2a2e-4f9a-81ab-0f97d6c294e6)

 ⑥. 관리자 마이페이지 화면

![image](https://github.com/user-attachments/assets/9257388d-17df-4e3e-8224-0dbe19ac845c)

<br/>

  
#### IA(Information Architecture)
![스크린샷 2024-09-03 210013](https://github.com/user-attachments/assets/992c6f28-af48-4b85-9cb6-96230b821b13)

<br/>

### 3.2. 기능설명
#### ` 홈 `
- **카테고리 버튼**
  - 원하는 카테고리 버튼을 누르면 해당 카테고리 관련 제휴를 볼 수 있습니다. <br/>

- **최신 등록 제휴 공지 알림 화면**
  - 가장 최근에 등록한 제휴 정보에 대해 간략하게 보여줍니다.
 
- **공지사항 미리보기**
  - 앱 관련 공지사항 제목을 미리볼 수 있습니다.

#### ` 디테일 `
- **카테고리 버튼 및 진행 중인 제휴만 보기**
  - 가로 스크롤을 통해 관심 있는 카테고리를 선택할 수 있고 진행 중인 제휴만 보게 필터링을 할 수 있어 정보를 효율적으로 얻을 수 있습니다.

- **제휴 공고 미리보기**
  - 대표 이미지, 제목, 앞의 내용 3줄을 간략하게 표현할 수 있으며 제휴 공고 미리보기 클릭 시 세부 제휴 정보를 볼 수 있습니다.

- **세부 제휴 정보**
  - 제휴 업체명 및 제휴 기간이 가장 처음에 나오며 그 뒤로 세부 제휴 내용을 볼 수 있고 가게 위치를 지도를 통해 대략적으로 파악할 수 있습니다. 마지막으로 이 제휴를 사용한 사람들의 리뷰를 열람할 수 있습니다.

#### ` 맵 `
- **제휴 가게 위치 정보**
  - 데이터베이스에 저장되어 있는 모든 제휴 가게들을 지도에 마커로 표현하였습니다. 또한, 내 위치 정보 활성화로 주변에 어떤 제휴 가게들이 있는지 대략적인 정보를 파악할 수 있습니다.

#### ` 사용자 마이페이지 `
- **내 정보 수정**
  - 회원 가입 시 입력했던 정보를 바꾸고 싶은 경우, 이 화면을 통해서 닉네임 및 전공을 변경할 수 있습니다.

- **내가 작성한 리뷰 목록**
  - 사용자가 작성한 리뷰를 확인하여 어떤 제휴를 사용하였는지를 확인할 수 있습니다.

#### ` 관리자 마이페이지 `
- **제휴 공지 작성 및 관리**
  - 관리자 인증을 받은 계정은 제휴 공지를 작성할 수 있습니다. 사진, 위치, 제휴 기간, 카테고리를 지정하여 제휴 정보를 등록할 수 있고, 이를 수정하는 것 역시 가능합니다.

<br/>


### 3.3. 기능명세서

#### `로그인 및 회원가입 (+비번 찾기)`
<img src="https://github.com/user-attachments/assets/fc45ab92-f87d-45ea-8306-a84945956a71" alt="image" width="300" height="750"/>
<img src="https://github.com/user-attachments/assets/88395a5e-12fd-41e9-ac3e-83c8ca34ccf1" alt="image" width="300" height="750"/>
<img src="https://github.com/user-attachments/assets/b5dfb42e-cf59-4676-b6ea-208c1aef33c4" alt="image" width="300" height="800"/>



|라벨|이름|상세|
|:---:|:----------------------------:|:---|
| S1  | 부산대학교 웹메일 입력        | - 부산대 웹메일 형식으로 입력 |
| S2  | 비밀번호 입력| - 회원가입 시 사용한 비밀번호 입력 |
| S3  | 로그인 버튼               | - 클릭 시 로그인|
| S4  | 비밀번호 찾기 버튼         | - 클릭 시 비밀번호 찾기 화면 이동 |
| S5  | 회원가입 버튼                        | - 클릭 시 회원가입 화면 이동 |
| S6  | 비밀번호 찾기 부산대 웹메일 입력          | - 부산대 웹메일 형식으로 입력|
| S7  | 비밀번호 재설정 버튼               | - 부산대 웹메일로 비밀번호 변경 링크 전송 |
| S8  | 부산대학교 웹메일 인증           | - 부산대 웹메일에서 인증 이메일을 받을 시 인증 성공 |
| S9  | 비밀번호 입력             | - 8자 이상 비밀번호 입력 |
| S10 | 비밀번호 확인                 | - 비밀번호 입력과 일치하는지 확인|
| S11 | 단과대학                        | - 본인 단과 입력 |
| S12 | 학과(부)/전공                        | - 본인 학과(부)/전공 입력 |
| S13 | 닉네임                        | - 사용할 닉네임 입력 |
| S14 | 관리자 인증코드                        | - 입력 시 관리자 계정 전환 |
| S15 | 회원가입                        | - 클릭 시 회원가입 성공 및 실패여부 확인 |

<br/>

#### `홈 화면`
<img src="https://github.com/user-attachments/assets/14716ce8-780d-478f-a121-eccf4c241201" alt="image" width="300" height="750"/>




|라벨|이름|상세|
|:---:|:----------------------------:|:---|
| S1  | 전체보기        | - 전체 제휴 가게 확인 |
| S2  | 술집| - 술집 카테고리 제휴 확인 |
| S3  | 카페               | - 카페 카테고리 제휴 확인|
| S4  | 문화         | - 문화 카테고리 제휴 확인 |
| S5  | 음식점&식품                        | - 음식점&식품 카테고리 제휴 확인 |
| S6  | 헬스&뷰티          | - 헬스&뷰티 카테고리 제휴 확인|
| S7  | 교육               | - 교육 카테고리 제휴 확인 |
| S8  | 의료&법           | - 의료&법 카테고리 제휴 확인 |
| S9  | 최신 제휴 공지 화면             | - 최신 제휴 공지 간략하게 열람 |
| S10 | 제휴 관련 공지사항                 | - 제휴 관련 공지사항 미리보기|


<br/>

#### `디테일 화면`
<img src="https://github.com/user-attachments/assets/14716ce8-780d-478f-a121-eccf4c241201" alt="image" width="300" height="750"/>




|라벨|이름|상세|
|:---:|:----------------------------:|:---|
| S1  | 전체보기        | - 전체 제휴 가게 확인 |
| S2  | 술집| - 술집 카테고리 제휴 확인 |
| S3  | 카페               | - 카페 카테고리 제휴 확인|
| S4  | 문화         | - 문화 카테고리 제휴 확인 |
| S5  | 음식점&식품                        | - 음식점&식품 카테고리 제휴 확인 |
| S6  | 헬스&뷰티          | - 헬스&뷰티 카테고리 제휴 확인|
| S7  | 교육               | - 교육 카테고리 제휴 확인 |
| S8  | 의료&법           | - 의료&법 카테고리 제휴 확인 |
| S9  | 최신 제휴 공지 화면             | - 최신 제휴 공지 간략하게 열람 |
| S10 | 제휴 관련 공지사항                 | - 제휴 관련 공지사항 미리보기|

<br/>

#### `사용자 마이페이지 화면`
<img src="https://github.com/user-attachments/assets/2edf7cd5-529a-44ba-a550-0d5ef88bfd8b" alt="image" width="300" height="750"/>





|라벨|이름|상세|
|:---:|:----------------------------:|:---|
| S1  | 내 정보 수정        | - 닉네임 및 전공 수정 |
| S2  | 내가 작성한 리뷰 보기| - 사용자가 작성한 제휴 관련 리뷰 확인 |
| S3  | 설정                        | - 푸쉬 알림 설정 |
| S4  | 공지사항          | - 앱 관련 공지사항 확인|
| S5  | 문의/버그 신고              | - 문의 오픈채팅방으로 이동 |
| S6  | 로그아웃           | - 클릭 시 로그아웃 |

<br/>

#### `관리자 마이페이지 화면`
<img src="https://github.com/user-attachments/assets/77c6e8ac-e718-4bad-bf6e-42f4704c7bfd" alt="image" width="300" height="750"/>






|라벨|이름|상세|
|:---:|:----------------------------:|:---|
| S1  | 제휴공지 작성        | - 제휴 공고 작성 |
| S2  | 제휴공지 관리| - 제휴 공고 수정 |
| S3  | 공지사항 작성               | - 제휴 관련 공지사항 작성|
| S4  | 공지사항 관리         | - 작성한 공지사항 수정 |
| S5  | 설정                        | - 푸쉬 알림 설정 |
| S6  | 공지사항          | - 앱 관련 공지사항 확인|
| S7  | 문의/버그 신고              | - 문의 오픈채팅방으로 이동 |
| S8  | 로그아웃           | - 클릭 시 로그아웃 |



### 3.4. 디렉토리 구조
```
app/                             # 애플리케이션의 주요 디렉터리
├── manifests/                   # AndroidManifest 파일이 있는 폴더
│   └── AndroidManifest.xml      # 애플리케이션의 구성 정보를 정의하는 파일
├── kotlin+java/                 # Kotlin과 Java 소스 코드가 있는 폴더
│   ├── com.example.myapplication/  # 패키지 경로 (기본 패키지)
│   │   └── (androidTest)        # Android 테스트 코드를 위한 디렉터리
│   │   └── (test)               # 유닛 테스트 코드를 위한 디렉터리
├── java/ (generated)            # 자동 생성된 Java 파일이 위치하는 폴더
├── res/                         # 리소스 파일들이 위치하는 폴더 (이미지, 레이아웃 등)
│   ├── drawable/                # 이미지 파일 (PNG, JPG 등)
│   ├── font/                    # 커스텀 폰트 파일
│   ├── layout/                  # XML 레이아웃 파일
│   ├── menu/                    # 메뉴 리소스 파일
│   ├── mipmap/                  # 아이콘 파일 (다양한 해상도)
│   ├── navigation/              # 네비게이션 그래프
│   ├── values/                  # 문자열, 색상, 스타일 등 XML 파일
│   └── xml/                     # 기타 XML 파일 (예: 프리퍼런스)
├── res/ (generated)             # 자동 생성된 리소스 파일이 위치하는 폴더
Gradle Scripts/                  # Gradle 빌드 스크립트와 설정 파일
├── build.gradle.kts (Project: My_Application)  # 프로젝트 전체 빌드 스크립트
├── build.gradle.kts (Module: :app)            # 모듈별 빌드 스크립트 (:app 모듈)
├── proguard-rules.pro (ProGuard Rules for ":app")  # 코드 난독화 규칙 파일
├── gradle.properties (Project Properties)    # 프로젝트 속성 파일
├── gradle-wrapper.properties (Gradle Version)  # Gradle 래퍼 설정 파일
├── libs.versions.toml (Version Catalog)      # 라이브러리 버전 관리 파일
├── local.properties (SDK Location)           # 로컬 개발 환경 설정 파일 (SDK 경로 등)
└── settings.gradle.kts (Project Settings)    # 프로젝트 설정 파일

```
<br/>


## 4. 설치 및 사용 방법
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
