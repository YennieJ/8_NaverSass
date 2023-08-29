# 8_NaverSass - 멋사 8조 github, Sass 프로젝트

## 목표

- github를 활용해서 협업 경험하기
- Sass 사용해서 협업 경험하기

---

## 구현

<img width="1676" alt="메인페이지" src="https://github.com/YennieJ/8_NaverSass/assets/108519185/bb6868cf-b50f-43ec-98bb-5e066512f0ed">
<img width="1680" alt="로그인페이지" src="https://github.com/YennieJ/8_NaverSass/assets/108519185/3d6f70a7-a26b-47b3-8092-08ae47d3681a">

## 🛠 Branch name 컨벤션

```
branch 이름은 '구현 내용-본인 이름' 으로 작성합니다.
본인 이름은 성을 포함하여 카멜 케이스로 작성합니다.
카멜 케이스
- 첫 글자는 소문자
- 중간 글자는 대문자
예시) memo-yeaJin
```

## :pencil2: Commit 컨벤션

| Tag Name | Description                               |
| -------- | ----------------------------------------- |
| Feat     | 새로운 기능을 추가                        |
| Design   | CSS 등 사용자 UI 디자인 변경              |
| Style    | 코드 포맷 변경, 세미 콜론 누락, 코드 수정 |
| Comment  | 필요한 주석 추가 및 변경                  |
| Refactor | 프로덕션 코드 리팩토링                    |
| Rename   | 파일 혹은 폴더명을 수정하거나 옮기는 작업 |
| Remove   | 파일을 삭제하는 작업                      |

```
Commit을 할 때 '태그: 구현 내용' 으로 작성합니다.
예시) Feat: 메모 UI
```

## <img src="https://sass-lang.com/assets/img/styleguide/seal-color.png" alt="react" width="35" height="35"/> Scss 컨벤션

** BEM (Block, Element, Modifier) 방식 **

```css
Class명을 'Block__Element--Modifier'으로 작성합니다.
예시) widgetboard__button----focused
```

---

### ⭐️1 회의록 (27-08-2023)

1.Github 코드리뷰 해보기

- 은진 -> 연정 -> 승무 -> 지은 -> 예니 -> 승규 -> 은진 PR 코멘트 달기

  2.Scss

- 승규님이 만들어주신 Mixin 사용해서 프로젝트에 적용하기
- 지은님이 만들어주신 공통 변수(color) 프로젝트에 적용하기

  3.BEM 방법으로 class naming 변경하기
