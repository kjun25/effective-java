## Item 44
#### java.util.function 패키지에 표준 함수형 인터페스를 다양하게 제공
#### 직접 구현하지 말고 표준형 함수형 인터페이스를 활용하는게 좋다.
#### API가 다루는 개념의 수가 줄어들어 익히기 쉽고 유용한 default method를 많이 제공해서 상호 운용성도 좋음
- 불필요한 함수형 인터페이스 대신 표준 함수형 인터페이스를 사용하라
---

+ java.util.function 패키지에는 총 43개의 인터페이스가 있음.
+ 기본 인터페이스 6개 정리
   * UnaryOperator<T>: T apply(T t)
   * BinaryOperator<T>: T apply(T t1, T t2)
   * Predicate<T>: boolean test(T t)
   * Function<T,R>: R apply(T t)
   * Supplier<T>: T get()
   * Comsumer<T>: void accept(T t)
