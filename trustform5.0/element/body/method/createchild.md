---
description: 해당 컨트롤에 하위에 자식 Element 를 생성하고 생성된 객체를 반환한다.
---

# createChild

## D

또한 생성된 자식 Element 는 반환된 객체를 통해 접근이 가능하다.

* 이미 존재하는 id 로 중복하여 createChild 를 사용할 경우, 자식 Element 는 만들어지지 않고, 이미 존재하는 Element 를 반환한다.

## S

```markup
 body.createChild(String elementName, String attributes)
```



