# Clean Code - Naming Rule
## 클래스명, 객체명은 명사 또는 명사구

클래스명, 객체명, 변수명은 명사 또는 명사구를 사용하되, 너무 보편적인 단어나 접미사로 빈번하게 사용되는 명사는 단독으로 사용하지 않는 것이 좋다.

``` Java
// 너무 보편적인 단어, 자주 사용되는 접미사는 단독으로 사용하지 않는 것이 좋다.
// public class Data { ... }
// public class Info { ... }

public class CompanyAddress { ... }

// 클래스명, 객체명은 명사나 명사구를 사용하는 것이 좋다.
// public class Require { ... }

public class Requisition { ... }
```
