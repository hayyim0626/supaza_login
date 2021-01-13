# 수파자 프론트엔드 과제

안녕하세요! 프론트엔드 개발자 홍예찬입니다. 과제에 대한 소스코드가 어떻게 이루어져있는지 README 파일을 통해 설명해드리도록 하겠습니다.

## 기술 스택

- React(React Hooks)<br>
- SCSS<br>
- React-Router-Dom(로그인 성공 시, 페이지를 넘어가기 위해 사용했습니다.)<br>

## 컴포넌트 단위 분류
가장 먼저, 재사용성을 고려하여 컴포넌트를 단위별로 분류했습니다.<br>
Navbar와 Footer의 경우, 로그인 페이지뿐만 아니라 다른 페이지에서도 재사용되기 때문에 따로 Components라는 폴더에 작업했습니다.<br>
그 이후, 로그인 페이지는 Pages 폴더에서 작업했습니다.<br>
각각의 컴포넌트는 App.js 파일에 모두 import하는 방식으로 구현했습니다. <br>
<img width="175" alt="20210113_235308" src="https://user-images.githubusercontent.com/68314696/104468195-836bd800-55fa-11eb-90fc-aba4a5aadbbe.png">

