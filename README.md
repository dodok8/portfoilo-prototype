# Portifolio-Prototype

포트폴리오 페이지에 사용할 기술 스택 페이지의 일부 구현입니다.

## 구현한 것

### portfoloi-cards-table

- [x] 배경에 비네팅 넣기
- [x] 카드 만들기
- [x] 카드에 리본 달기
- [x] 리본에 호버시 툴팁 보여주기
- [x] Grid System을 이용한 정렬

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

