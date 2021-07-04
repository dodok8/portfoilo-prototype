# Portifolio-cards-table

포트폴리오 페이지에 사용할 기술 스택 페이지의 일부 구현입니다.

## 구현한 것

- [ ] 카드 만들고 정렬하기

  - <https://studiomeal.com/archives/533>

  - Grid System 으로 작성 중

- [x] 카드 오버플로우 시 내용 보여주기

  - `:after`와 `before`, `:hover`활용,`opacity` 조정함.

- [X] 카드에 리본 달기

  - <https://codepen.io/wesleycole/pen/Gaufy>

  - <https://codepen.io/nxworld/pen/oLdoWb>

  - 이 둘을 참고해서 작업 중

  - `overflow: hidden`을 사용해서 잘라버릴 수 있다.

- [x] 배경에 비네팅 넣기

## 궁금한 것

- `<body>`는 뭔가 특이한 성질이 있나?

```CSS
{
  position: fixed;
  width: 100%;
  height: 100%;
  content: "";
  box-shadow: 0px 0px 220px black inset;

  pointer-events: none;
  z-index: 1000;
}
```

이걸 `body`에 달던, `body`의 의사 객체에 달던 이상한 경계가 생긴다. 왜 생길까?
