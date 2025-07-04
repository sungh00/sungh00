## 1. 홈페이지 소개

첫 번째로 홈페이지를 만든 사람의 이름을 제 이름으로 넣고, 그 다음 문장에 소속 대학과 나이를 적었습니다.

다음으로 "My Skills"에선 제가 다룰 수 있는 프로그래밍 언어를 사진으로 소개하고

"Projects"에서는 나중에 할 예정인 프로젝트 5개를 소개 했습니다.

"Desired Job Role"에서는 나중에 취직할 때 희망하는 직무 2가지를 소개했습니다.

또한 테마를 활용하지 않고 직접 작성하였습니다.

(홈페이지 주소: https://sungh00.github.io/sungh00/)
(Github 주소 : https://github.com/sungh00/sungh00)


## 2. My Skills

My Skills 부분에서는 제가 조금이라도 다룰 수 있는 프로그래밍 언어들을 나열했고

순서대로 **C#, Linux, Java**입니다.

## 3. Projects

Projects에서는 제가 나중에 실행할 예정인 프로젝트를 순서대로 나열했습니다.

**AI Development**와 **Security Program**는 현재 제가 생각하고 있는 진로 프로젝트들이기 때문에 1, 2순위로 나열했고 

3번부터 5번 프로젝트까지는 제가 취직하기 전에 스스로 만들어볼 예정인 프로젝트들로 구성했습니다.

## 4. Desired Job Role
Desired Job Role에서는 제가 희망하는 직무 2가지를 설명하고 있습니다.

그 중 2개가 바로 **AI Development**와 **Security Program**입니다.

 **AI Development**는 중학생 시절부터 계속 생각해왔던 진로입니다. 
 
 미래엔 AI 시대가 찾아올텐데 그 시기를 직접 AI 개발 프로젝트를 진행하는 개발자가 되고 싶습니다.

 **Security Program**도 비슷한 맥락입니다.

 AI 하면 가장 먼저 떠오르는 문제점은 바로 "보안"입니다.

 보안만 안전하게 확보된다면 개인적으로 AI는 정말 다양하게 활용될 수 있다고 생각합니다.

 그렇기에 스스로 보안 프로그램을 만드는 직업을 경험해보고 싶습니다.

 ## 5. 기능 추가

 ## 5-1 css 스타일 추가

css스타일을 추가해서 외부 스크립트 형식으로 작성했습니다.

내부 스크립트로 작성하는 것 보단 외부 스크립트로 작성하는 형식이 훨씬 보기 깔끔할 것 같았습니다.

`<link rel="stylesheet" href="source.css">`로 코딩했고 7번째 코드에 해당하며 "source"라는 css 스타일을 내부 스크립트에 적용시켰습니다.

## 5-2 h1과 h2 class 추가

홈페이지를 만든 사람이 누군지 소개해주는 문구가 필요 했습니다.

13번 코드의 `<h1 class="profile-title">Sung Ho Park Homepage</h1>`으로 코딩했고 해석해보면

h1 스타일로 크게 설정했으며 profile-title이라는 클래스 이름으로 지정했습니다. 또한 해당 코딩의 적용 문구는 "Sung Ho Park Homepage"입니다.

그 뒤 14번 코드의 `I'm Hnu student, 23years-old`라는 문구도 h1 코딩과 같은 개념으로 코딩했으며 h2 스타일로 적용해 h1보다는 작게 보이게 했습니다.

이 뒤에도 "My Skills"나 "Projects", "Desired Job Role"에도 h2 class 스타일을 적용했으며, 각각 17, 29, 37번 코드에 해당합니다. 

## 5-3 이미지 추가

저의 모습을 올리고, 스스로 만든 홈페이지다 보니 배경 사진도 필요하고, Skill들을 나타내는 방법도 이미지로 표현했기 때문에 "이미지 추가"기능을 넣었습니다.

저의 사진은 12번 코드의 `<img src="Myprofile.jpg" class="profile-img" />` 코드로 작성했고 해석해보면

img 태그를 사용해 이미지 추가하는 기능을 넣었고, src="Myprofile.jpg"는 src라는 이미지 경로를 나타내는 명령어를 사용하였습니다.


또한 Myprofile.jpg은 jpg파일이 같은 경로 안에 있음을 나타냅니다. 이 이미지를 식별하기 위해 profile-img라는 class 클래스 스타일을 부여했습니다.

그 다음 배경사진은 css스타일 8번 코드, skill 사진들은 20, 23, 26번 코드에 해당합니다.

## 5-4 div기능을 이용해 구역 설정

다양한 project와 희망 직무를 설명할 수 있게 div 기능을 추가하여 칸을 구분하였습니다.

30번 코드의 `<div class="text-wrapper">` 코드입니다.

먼저 뒤에 나올 div기능들을 text-wrapper라는 클래스 스타일로 묶음과 동시에

따로 css스타일을 적용시켜 글자들을 예쁘게 수정했습니다.

그 다음 31번 코드의 `<div>Project 1 : AI Development (planned)</div>` 코드는 말 그대로 div로 해당 블록을 따로 나누고 

그 안에 들어갈 내용을 "Project 1 : AI Development (planned)"로 작성했습니다.

그 뒤에 같은 코드들이 32번 33번 등에도 반복되어 project들을 설명해줍니다. 

또한 38~40번에 해당하는 코드들도 같은 방법으로 적용 시켜 코딩했습니다.
