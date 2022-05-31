# [Scroll Page](https://mingnana.github.io/Portfolio_ScrollPage/nuka.html)


#### 1. 프로젝트 소개
```md
* 스크롤 기능을 학습하기 위해 만든 페이지입니다.
```

#### 2. 프로젝트 기간
```md
* 2022.05.21 ~ 2022.05.22
```

#### 3. 사용 stack 및 tool
```md
1) Front-end stack 
  - HTML5, CSS3, JQuery로 구현 

2) IDE
  - Visual Studio Code
```

#### 4. 프로젝트 설명
```md
* 윈도우의 스크롤 값이 일정값을 넘어갈때 이미지가 변환되도록 구현
  글자부분의 경우, 지정된 스크롤 위치값과 일치하면 (if, else if) 나타나도록 구현
```
<img src="https://user-images.githubusercontent.com/96216178/171088748-7dbde05a-2ca7-4ed7-80fa-47102f0c9851.gif">
<img src="https://user-images.githubusercontent.com/96216178/171088902-e8894685-f70d-4a65-b590-f41365d65db9.gif">

#### 5. 프로젝트 Review

```md
 1) HTML 파일을 열었을때는 부드럽게 넘어가지만 서버를 통해서 열었을때 이미지가 불러오는 속도때문인지 상당히 느리게 구현되는 이슈발생
    -> 해상도크기에 따른 스크롤값의 차이인듯하여 스크롤값을 수정해봤지만 여전히 나타나지않음
    -> 깃허브라는 무료도메인을 통해 웹호스팅을 하기 때문에 엑세스속도가 느리게 나타나는 현상으로 추정. 빠른 시일내에 다른 도메인을 통해 배포를 해봐야 할것같음
 2) if문이 끝났을때도 계속 이미지가 나타나는 이슈 발생
    -> return false가 인식되지 않고, else if로 이상의 값을 넣어봤지만 해결되지 않음
    -> javascript와 jquery에 대해 더 많이 공부해야 할것같음
 3) 스크롤을 내렸을때 이미지가 나타나는 코드는 if, elseif로만 구현을 했기 때문에 더 심도깊은 코드개발이 필요할듯함
```

