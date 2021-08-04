### 자바 Long 입력 문제

---

개요:

프로그래머스 문제를 풀다가 생긴 오류 the literal 50000000000000 of type int is out of range

```java
long L = 5000000000; 
```



Long 의 범위는 이론상 -9223372036854775808 ~ 9223372036854775807 이기 때문에 에러가 나지 말아야하는데?



뒤의 값을 Java에서 int 값으로 인식해서 생긴 오류이다.



따라서



```java
long L = 5000000000L;
```



이 숫자는 Long입니다 라는 표시를 해주면 된다!



##### 관련문제

---

프로그래머스 - [정수 제곱근 판별](https://programmers.co.kr/learn/courses/30/lessons/12934)

