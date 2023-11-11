# display

## display : none

: 요소를 렌더링하지 않도록 설정하고 **visibility** 속성을 **hidden**으로 설정한 것과 달리 영역도 차지하지 않는다.

## display : inline

밑줄 등 **글자나 문장에 효과를 주기 위해 존재하는 단위**라고 할 수 있다.

## display : block

:요소를 **block 요소**처럼 표시합니다. 따라서 요소 앞 뒤로 줄바꿈 됩니다.

## display : inline-block

- 줄바꿈이 이루어지지 않는다.
- block처럼 width와 height를 지정 할 수 있다.
- 만약 width와 height를 지정하지 않을 경우, lnline고 컨텐츠만큼 영역이 잡힌다.

# Flex

**Flex**의 속성은 컨테이너에 적용되는 속성과 아이템에 적용되는 속성으로 나뉨

**justify-content** : 가로선 상에서의 정렬 방식

- flex-start : 컨테이너의 왼쪽으로 정렬
- flex-end : 컨테이너의 오른쪽으로 정렬
- center : 컨테이너의 가운데로 정렬
- space-between : 요소들 사이에 동일한 간격을 둠
- space-around : 요소들 주위에 동일한 간격을 둠

**align-ltems** : 세로선 상에서의 정렬 방식

- flex-start : 컨테이너의 최상단으로 정렬

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/697b658c-e5eb-4d9c-9536-97d4f05003d4/168c8e20-5a53-461f-8265-e27e7bff6f5e/Untitled.png)

- flex-end : 컨테이너의 최하단으로 정렬

![스크린샷 2023-11-09 오후 11.33.34.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/697b658c-e5eb-4d9c-9536-97d4f05003d4/249b2f63-0a39-4cf9-89ca-a16f310cbd34/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-09_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_11.33.34.png)

- center : 컨테이너의 세로 축의 중앙으로 정렬

![스크린샷 2023-11-09 오후 11.33.53.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/697b658c-e5eb-4d9c-9536-97d4f05003d4/70d7f0b9-6b87-4f9f-b480-ad43e53ac498/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-09_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_11.33.53.png)

- baseline : 요소들을 컨테이너의 시작 위치에 정렬

![스크린샷 2023-11-09 오후 11.34.23.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/697b658c-e5eb-4d9c-9536-97d4f05003d4/915c28a2-d6ed-4f6d-94d8-5fe37580eeb9/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-09_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_11.34.23.png)

- stretch : 요소들을 컨테이너에 맞도록 늘림