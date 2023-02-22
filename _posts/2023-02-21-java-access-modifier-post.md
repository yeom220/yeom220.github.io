---
title: "Java 접근제한자"
except: "Java 접근제한자의 종류와 사용목적 등을 정리한 포스트"

categories:
  - Java
tags:
  - [TIL, Java, Access Modifier]
last_modified_at: 2023-02-21
---

### 접근 제한자
접근 제한자의 종류는 **'public, protected, (default), private'** 등이 있다.<br/>
접근 제한자는 객체지향(OOP)적인 코드 작성을 위해 사용하며 2가지 이점이 있다.<br/> 
1. 외부에 불필요한 자료는 노출시키지 않는다. *(캡슐화)*
2. 사용자 관점에서 꼭 필요한 것만 볼 수 있어 편리하다.
접근 제한자는 다음과 같이 4가지로 구분할 수 있다. 
   
|구분|다른 패키지|사용 예|
|:-----:|:-----:|:-----:|
|public|모두 접근허용|public String name;|
|protected|다른 패키지 일부허용(상속클래스만 접근 허용)<br/> 동일 패키지 내 접근허용|protected String name;|
|(default)|동일 패키지 내 접근허용<br/> 제한자를 입력하지 않을 경우 default 타입이 된다.|String name;|
|private|동일 클래스에서만 접근 허용|private String name;|
   
### 예시
```java
public class ProductVo1 {
	public String productNo;	// public - 모두허용
	protectd String productName;	// protectd - 동일패키지, 상속
	private int price;		// private - 동일클래스
	int type;			// default 접근 - 동일패키지
}
```
###### 참조
* [자바 프로그래밍 100% 실전 가이드 세트](http://www.yes24.com/Product/Goods/73300092)
