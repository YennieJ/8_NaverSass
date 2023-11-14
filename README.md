# 8_NaverSass - 멋사 8조 github, Sass 프로젝트

조장: <a href="https://github.com/YennieJ">이예진</a>

조원:  <a href="https://github.com/eunjingrove">박은진</a>   <a href="https://github.com/GoodSilver9">이승무</a> <a href="https://github.com/cutieun">이지은</a>  <a href="https://github.com/Seunggyu008">정승규</a> <a href="https://github.com/yeonjeonge-e">최연정</a>

## 목표

- github를 활용해서 협업 경험하기
- Sass 사용해서 협업 경험하기

---

## 구현

<img width="1676" alt="메인페이지" src="https://github.com/YennieJ/8_NaverSass/assets/108519185/bb6868cf-b50f-43ec-98bb-5e066512f0ed">
<img width="1680" alt="로그인페이지" src="https://github.com/YennieJ/8_NaverSass/assets/108519185/3d6f70a7-a26b-47b3-8092-08ae47d3681a">


---

### ⭐️1차 회의록 (2023-08-25)

예진:메모 / 은진:검색 / 승무:로그인 / 지은:뉴스 / 승규:로그인페이지 / 연정:nav

1. 하드 코딩으로 기본 UI틀 완성하기

---
### ⭐️2차 회의록 (2023-08-27)

1. 은진 -> 연정 -> 지은 -> 승무 -> 예진 -> 승규 -> 은진
   PR comment 하기

2. <a href="https://github.com/Seunggyu008">정승규</a>가 만든 Sass Mixin 사용하기
   <img width="1260" alt="스크린샷 2023-11-14 오후 8 11 56" src="https://github.com/YennieJ/8_NaverSass/assets/108519185/3bf1d10f-eb84-452f-9d7c-1e1a3b49f1a9">

3. <a href="https://github.com/cutieun">이지은</a>이 만든 Sass 변수 - color 사용하기
   <img width="1260" alt="스크린샷 2023-11-14 오후 8 14 21" src="https://github.com/YennieJ/8_NaverSass/assets/108519185/92d70626-3f67-49b2-b1c0-0066daadbd69">

4. BEM class명으로 컨벤션 변경되었음으로 적용하기

---
### ⭐️3차 회의록 (2023-08-31)

1. 은진 -> 승규 -> 예진 -> 승무 -> 지은 -> 연정 -> 은진
   PR comment 하기
2. <a href="https://github.com/yeonjeonge-e">최연정</a>이 만든 Sass 반복문 코드 리뷰
   <img width="978" alt="스크린샷 2023-11-14 오후 8 21 23" src="https://github.com/YennieJ/8_NaverSass/assets/108519185/ee643f10-db41-46b0-aa9c-11ac991d5993">
    .serviceList__icon 클래스에 대한 스타일을 정의하며, $icons 맵에서 각 아이콘과 해당 속성을 반복하여 가져와 동적으로 선택자를 생성합니다. 각 아이콘에 대해 생성된 선택자는 해당 아이콘의 클래스를 나타내며, 이후 set-sprite 믹스인을 호출하여 아이콘에 대한 background 속성을 설정합니다. 이렇게 함으로써 중복된 코드를 피하고 효율적으로 여러 아이콘에 대한 스타일을 처리할 수 있습니다.

---
### ⭐️4차 회의록 (2023-09-10)
- <a href="https://github.com/YennieJ">이예진</a> rebase 진행 방법 공유
  ![rebase,merge](https://github.com/YennieJ/8_NaverSass/assets/108519185/722f8b5e-5ede-4db2-b153-a22cabd5d5eb)

---
### ⭐️5차 회의록 (2023-09-18)
1. <a href="https://github.com/eunjingrove">박은진</a> 시멘틱 태그를 사용하여 전체 html 수정
2. <a href="https://github.com/GoodSilver9">이승무</a> 전체 CSS 스타일 수정
3. 완료된 개인 브랜치 삭제

---
### ⭐️6차 회의록 (2023-09-18)
전체 코드 리뷰, 이 프로젝트를 통해 느낀 점

<a href="https://github.com/yeonjeonge-e">최연정</a>: SCSS 언어의 중첩 선언, @import, @mixin 등을 활용하니 코드의 가독성과 개발 효율이 높아져 왜 현업에서 많이 사용하는지 알게 되었고, GitHub를 통해 팀원들과 코드 리뷰와 피드백을 주고 받으며 프로젝트를 효율적으로 관리하고 협업 능력을 향상시킬 수 있다는 점에서 Git의 중요성을 깨닫게 되었다.

<a href="https://github.com/Seunggyu008">정승규</a>: Sass는 재사용성, 가독성이 기존 CSS보다 좋아 유지보수에 좋고 동적인 프로그래밍 기능도 추가되어 유용했다. Git은 파고들수록 어려웠고 특히 브랜치 관리는 더더욱 그랬던 거 같다. 다음 프로젝트 진행 시 다른 협업 툴을 적극적으로 사용하는 것도 좋아보인다.


<a href="https://github.com/cutieun">이지은</a>: Sass가 협업에 좋다는 게 더 와닿았다. 공통적으로 사용되는 부분은 변수나 함수 처리해서 사용하니 가독성도 좋고 중복 코드도 줄어들어 좋았고 Git은 아직도 익숙하지 않아 더 많이 경험을 해봐야겠다.

<a href="https://github.com/GoodSilver9">이승무</a>: Sass를 쓰면서 현업에서도 규정에 맞게 CSS를 작업할 때 mixin 방식으로 함수로 저장해둔 규격에 맞게 작업을 할 수 있으니 유지보수 관리에 매우 좋다고 느꼈습니다. 또한 중첩(Nesting) 방식으로 어느 클래스의 부모 요소가 무엇인지 볼 수 있어서 가독성이 좋았습니다. 깃허브 처음으로 협업을 해보았는데 생각보다 수월하지 못했고 브랜치와 PR의 사용도를 알게되었습니다. 다음 협업 프로젝트를 할 때는 훨씬 더 잘할 수 있을 거 같습니다.

<a href="https://github.com/eunjingrove">박은진</a>: 프로젝트에 Sass를 적용하면서 코드의 가독성과 재사용성을 개선하는 방법을 배울 수 있었다. Git rebase 하는 과정이 쉽지 않았지만 팀원들과의 협력과 도움을 통해 프로젝트를 완료할 수 있었고 더 나은 개발자로 성장할 수 있는 기회였다.

<a href="https://github.com/YennieJ">이예진</a>: Sass의 코드 재사용성을 경험해보니 유지보수하기 수월하고 코드의 통일성으로 가독성이 뛰어나 현업에서 중간에 투입 되었을 때도 코드를 분석하기 다른 툴보다 쉬울 것 같아 공부해보길 잘했다는 생각이 들었습니다. GitHub을 사용한 협업으로 Issues를 사용해 보지 못한 것이 아쉬웠지만 PR을 통해 코드 리뷰를 하고 팀원들의 진행 상황을 명확히 알 수 있었던 점과 rebase와 merge를 경험함으로 다음 프로젝트에서 경험해 보지 못한 팀원들에게 조금이라도 도움이 될 수 있을 것 같습니다.


---
#### 🛠 Branch name 컨벤션

```
branch 이름은 '구현 내용-본인 이름' 으로 작성합니다.
본인 이름은 성을 포함하여 카멜 케이스로 작성합니다.
카멜 케이스
- 첫 글자는 소문자
- 중간 글자는 대문자
예시) memo-yeaJin
```

#### :pencil2: Commit 컨벤션

| Tag Name | Description                               |
| -------- | ----------------------------------------- |
| Feat     | 새로운 기능을 추가                        |
| Design   | CSS 등 사용자 UI 디자인 변경              |
| Style    | 코드 포맷 변경, 세미 콜론 누락, 코드 수정 |
| Comment  | 필요한 주석 추가 및 변경                  |
| Newfile  | 새로운 파일 생성,복사                     |
| Refactor | 프로덕션 코드 리팩토링                    |
| Rename   | 파일 혹은 폴더명을 수정하거나 옮기는 작업 |
| Remove   | 파일을 삭제하는 작업                      |

```
Commit을 할 때 '태그: 구현 내용' 으로 작성합니다.
예시) Feat: 메모 UI
```

#### <img src="https://sass-lang.com/assets/img/styleguide/seal-color.png" alt="react" width="35" height="35"/> Sass 컨벤션

** BEM (Block, Element, Modifier) 방식 **

```css
Class명을 'Block__Element--Modifier'으로 작성합니다.
예시) widgetboard__button--focused
```



