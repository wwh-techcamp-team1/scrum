
# 테크캠프 1조 데일리 미팅 - 22일차 (08.01 화)

## 의견
- 두호 다인 조 간단한 메소드에서 알 수 없는 에러가 발생해서 해결하지 못했다. 같이 한번 봐야 할 것 같음.
- 금요일까지 기획서를 작성해야하는데 의식적으로 조금 생각해볼 필요가 있을 것 같다.
- 점심 먹으면서 얘기해 보면 될 것 같다.
- 이번 3단계에서 배포 스크립트 자동화는 코드를 같이 짜고 페어 각자별로 진행하면서 실제 배포 과정을 경험해 보면 좋겠다.
- 진도가 너무 늦는다 싶으면 야근을 해야할 것 같음. 이번주에 4단계까지 끝내는 걸 목표로 해보자.
## 공유
- [Javascript DOM](https://tramyu.github.io/js/javascript-dom/)
예전에 DOM 관련해서 살펴본 내용
- [Javascript Event](https://tramyu.github.io/js/javascript-event/)
예전에 자바스크립트 이벤트에 대해 살펴본 내용, addEventListener 메소드가 모든 Object에서 사용할 수 있는 이유, 이벤트 버블링 캡처링에 대한 내용
- [SpringBoot로 웹 서비스 출시하기](http://jojoldu.tistory.com/255?category=635883)

  DTO는 Entity를 사용해도 되지만, Entity는 DTO에 대해 전혀 모르게 코드를 구성해야한다.  
  Entity는 말 그대로 가장 core한 클래스인 반면, DTO는 View 혹은 외부 요청에 관련 있는 클래스이다.  
  Entity가 DTO를 사용하게 되면, 그때부터 View/외부요청에 따라 DTO뿐만 아니라 Entity까지 변경이 필요하게 된다.  
  또한, 다른 DTO도 필요하다고 하면 다시 Entity에 toDto2와 같은 메소드가 추가되는데, 모든 변화에 맞춰 Entity 변경이 필요하게 된다.  
  프로젝트 규모가 커져 프로젝트를 분리해야할때도 Entity가 DTO를 의존하고 있으면 분리하기가 굉장히 어렵기 때문에 DTO가 Entity에 의존하도록 코드를 꼭꼭 작성하자!  

## 어제까지 진도
- pair1(두호, 다인) : 2단계 완료
- pair2(규남, 도연) : 2단계 완료

## 오늘 일정
- 페어 바꾼 후 3단계 진행
