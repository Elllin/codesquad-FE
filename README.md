## 이번주 배운 것

- prototype
- Event Delegation

## [미션] 검색자동완성

- JSON형태의 mock 데이터를 만들어서 응답하도록 한다.
- 검색UI와 검색자동완성노출UI를 별개의 prototype패턴의 객체로 각각 구현한다.
- 검색어 입력View, 검색자동완성View를 따로 만든다.
- Event 등록은 delegation방법을 적극 활용한다.
- fetch API 활용

## 코드리뷰

1. 잘된 점

   - 전체적으로 모듈분리 관리가 잘 된 코드
   - 재사용을 위해 sub-routine으로 분리한점

2. 아쉬운 점

   - return 문 뒤에 복잡한 식을 두지 않고 변수에 담아서 변수를 return하자
   - cardMeun에서 Delegation으로 event를 등록하지 않은 것
   - [config파일] 객체 생성에 필요한 값을 분리한건 그렇게 좋지 않다.
     객체에 어떤 값이 필요 할 지 보이는 게 좋다.
     에러메시지나 어떤 상수값들이 많다면 분리해도 좋다.

   ## 느낀점

   이번에는 재사용을 생각하며 구현해봤는데 생각보다 너무 어려웠다. 지금까지 재사용을 생각하며 구현한 적이 없었는데 이번 미션을 통해서 너무 큰 깨달음을 얻은 것 같다. 재사용은 어렵기 때문에 앞으로도 꾸준히 연습해야 할 것 같다.
