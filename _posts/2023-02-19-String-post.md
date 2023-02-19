---
title: "Java String 생성방식 비교 (리터럴 vs new 연산자)"
except: "Java String 생성방식 비교"

categories:
  - Java
tags:
  - Java, String
last_modified_at: 2023-02-19T23:07:00
---

Java 에는 변수타입이 2가지 있다. 기본형과 참조형인데 String의 경우 참조형 변수 타입이다.   
String 객체 생성 방식에는 리터럴방식과 생성자 호출방식이 있는데 주로 리터럴 방식이 쓰인다.   
String 리터럴 방식과 생성자 호출방식에는 몇가지 차이점이 있는데 리터럴 방식으로 생성된 String 객체는 Heap 메모리 내부의 String constants pool 영역에 할당되고 생성자 호출방식은 일반 객체들과 동일하게 Heap 메모리 영역에 할당된다.
 
