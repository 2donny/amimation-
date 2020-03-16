/* 
amimation 속성을 이용해서 요소에 애니메이션 효과를 적용해봅시다.

animation: 애니메이션이름 duration timing-function delay infinite;
  이런 형식으로 속성을 지정해줍니다.
  
.box:hover { } --> 요소에 커서를 올릴 때 배경색상을 dodgerblue로 주고, 
                   animation-play-state: paused;로 효과를멈춰줍니다.
                   
.box:hover::after {content:"Paused!"} ==> 이 코드를 통해서 요소에 마우스 커서를 올릴 때 content를 통하여 text를 Paused!가 출력되게 해줍니다.
