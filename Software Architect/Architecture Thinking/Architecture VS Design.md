> 아키텍처와 설계의 차이점은 모호한 경우가 많다.

![](https://i.imgur.com/QMR2yvX.png)
<center>아키텍트와 설계를 구분하는 기존 시각</center>

```
아키텍트는 비즈니스 요구사항을 분석해서 아키텍처 특성을 도출/정의하고 어떤 아키텍처 패턴과 스타일이 해당 문제 영역에 가장 알맞는지 선택하여 각종 컴포넌트(시스템 구성 요소)를 만든다.

위 그림은 문제가 많다.

아키텍트와 개발자를 나누는 가상의 물리적 장벽을 통과하는 단방향 화살표가 바로 아키텍처와 연관된 모든 문제의 원인이다.
아키텍트가 내린 결정이 개발팀에서 전혀 쓸모가 없는 경우가 있음에도 불구하고, 개발팀이 아키텍처를 변경하기로 결정한 내용이 다시 아키텍트에게 전달되는 일은 거의 없다.

아키텍트가 개발팀과 완전히 단절되어 있기 때문에 원래 의도했던 아키텍처는 점점 요원해지는 것이다.
```

![](https://i.imgur.com/tM8JaA6.png)
<center>아키텍처는 협력을 통해 만들어 간다.</center>

요즘 시스템 아키텍처는 매 프로젝트 단계마다, 또는 매 이터레이션(iteration)마다 끊임없이 변화하고 발전하기 때문에 소프트웨어 프로젝트를 성공으로 이끌려면 아키텍트와 개발팀이 뭉쳐야 한다.

> 아키텍처는 어디까지고 설계는 어디서부터인가
> 그런 경계는 따로 없고, 아키텍처, 설계 모두 소프트웨어 프로젝트 생명 주기의 일부로서 항상 서로 동기화되어야 성공할 수 있다.