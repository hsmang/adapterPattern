# DesignPattern 공부

## Adapter Pattern
```
Adapter 패턴은 기존 클래스를 재사용할 수 있도록 중간에서 맞춰주는 역할을 한다.

예를들면 직류 120v를 사용하는 노트북을 교류 220v 에서 우리는 아무 문제없이 사용할 수 있다. 
이는 중간에 AC어댑터가 변환을 해주기 때문이다. 
이처럼 프로그램을 작성하다보면 기존에 만들어 놓은 클래스를 재사용하고 싶어도 수정하지 않으면 사용할 수가 없다.
이때 어댑터 클래스를 만들어서 재사용이 가능하게 해준다.

adapter 패턴은 2가지 형태가 있다.
- 클래스 adapter 패턴 : 상속을 이용한 어댑터 패턴
- 인스턴스 adapter 패턴 : 위임을 이용한 어댑터 패턴

SOLID 중에서 개방폐쇄 원칙(OCP)를 따른다.

com.han.design.adapterPattern 참고
```



