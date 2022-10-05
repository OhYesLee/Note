# Java - 거듭제곱 계산, Math.pow()

상태: 진행 중
작성일시: 2022년 10월 5일 오전 10:45

`Math.pow()`를 이용하여 거듭제곱을 계산할 수 있습니다. pow는 power를 의미하고, power의 뜻은 거듭제곱입니다.

`pow()` 인자로 a와 b를 전달하며, a의 b 제곱이 리턴됩니다. 즉, a를 b번 곱한 값이 리턴됩니다.

`// Math.java
public static double pow(double a, double b)`

다음과 같이 3.2의 3제곱을 계산할 수 있습니다.

`double result = Math.pow(3.2, 3);
System.out.println(result);`

실행해보면 약 32.76이 리턴됩니다. 이 값은 `3.2 * 3.2 * 3.2`와 같습니다.

`32.76800000000001`

int로 변환하고 싶다면 다음과 같이 직접 형변환해줘야 합니다.

`int result = (int) Math.pow(3.2, 3);`