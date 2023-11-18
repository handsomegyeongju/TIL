## flex-direction

: flex container 내의 아이템을 배치할 때 사용할 주축 및 방향(정방향, 역방향)을 지정합니다.

- row :  왼쪽에서 오른쪽으로 아이템이 흐르는 가로 방향이다
- row-reverse : row와 비슷하며 반대로 배치가 된다
- column : 아이템들이 위에서 아래로 세로 방향으로 배치가 된다
- column-reverse : column 과 비슷하며 반대로 배치가 된다
    
    ![스크린샷 2023-11-13 오후 11.11.28.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/697b658c-e5eb-4d9c-9536-97d4f05003d4/f48face8-e14b-4e1b-9649-736c3d746057/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_11.11.28.png)
    

## flex-wrap

- nowrap : 기본값이며 줄바꿈을 하지 않고 더 이상 줄어들수 없을 때 container 밖으로 빠져나간다
- wrap : item의 witdh가 줄어들지 않고 item이 들어갈 공간이 없으면 다음 줄로 이동된다.
- wrap-reverse : wrap의 역순으로 정리 된다

![스크린샷 2023-11-13 오후 10.59.08.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/697b658c-e5eb-4d9c-9536-97d4f05003d4/e41bde52-8f21-4277-a26d-5c97d8d469cf/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_10.59.08.png)

## align-items

: align-items 속성은 콘텐츠 아이템의 내부 상하관계 정렬 상태를 설정합니다.

- stretch : 요소의 정렬 상태를 기본 값으로 한다
- center : 요소의 정렬 상태를 가운데로 한다
- flex-start : 요소의 정렬 상태를 위쪽으로 한다
- flex-end : 요소의 정렬 상태를 아래쪽으로 한다
- baseline : 요소의 정렬 상태를 폰트를 기준으로 한다
    
    ![스크린샷 2023-11-13 오후 11.11.04.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/697b658c-e5eb-4d9c-9536-97d4f05003d4/4d322feb-2e69-474d-a0e7-4debb25eb63a/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-11-13_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_11.11.04.png)