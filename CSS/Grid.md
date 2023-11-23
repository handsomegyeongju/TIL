## Flex 와 Grid의 차이점

- **Flex**는 1차원으로 수평, 수직 영역 중 하나의 방향으로만 레이아웃을 나눌 수 있습니다.
- **Grid**는 2차원으로 수평 수직을 동시에 영역을 나눌 수 있습니다.

![스크린샷 2023-11-14 오후 11.16.41.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/697b658c-e5eb-4d9c-9536-97d4f05003d4/2a0ac481-dec6-400f-b454-d3d1626472c9/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-14_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_11.16.41.png)

- grid-template-rows : 행의 크기를 정의한다
- grid-template-columns : 열의 크기를 정의한다
- grid-template-area : 영역의 이름을 참조해 탬플릿 생성

## 아이템 속성

### gird-row
#### 반대를 해줄수 있다

- grid-row-start : 그리드 아이템의 행 시작 위치 지정
- grid-row-end : 그리드 아이템의 행 끝 위치 지정
- grid-row : grid-row-start 와 grid-row-end 의 단축 속성

### gird-column

- grid-column-start : 그리드 아이템의 열 시작 위치 지정
- grid-column-end : 그리드 아이템의 열 끝 위치 지정
- grid-column : grid-column-start 와 grid-column-end 의 단축 속성

CSS 그리드 (CSS Grid):

웹 디자인에서 CSS 그리드는 레이아웃을 구성하기 위한 CSS 속성 중 하나입니다. 행과 열을 정의하여 웹 페이지의 레이아웃을 효과적으로 설계하는 데 사용됩니다.