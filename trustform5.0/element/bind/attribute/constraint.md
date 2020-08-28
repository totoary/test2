---
description: 제약조건을 지정하여 올바른 값인지 판단하는 속성
---

# constraint

## DESCRIPTION

constraint 는 제약조건을 지정하며 그 제약조건에 따라 값이 올바른\(valid\) 값인지 올바르지 않은 \(invaild\) 값인지 판단할 수 있다. 또한 constraint 는 항상 type 속성과 함께 사용하며, 수식의 조건에 맞는 값이 오면 xforms-vaild 이벤트가 발생하고 조건에 맞지 않는 값이 오면 xforms-invalid 이벤트가 발생한다.

xforms-valid 와 xforms-invalid 이벤트는 최초 로딩시점과 model.revalidate\(\) 가 수행될 때와 사용자가 입력값을 바꾸거나 model.refresh\(\) 되는 시점에서 발생한다. xforms-invaild 이벤트를 사용하여 데이터의 유효성을 체크할 수 있다.

{% hint style="info" %}

bind 창을 통해서 생성시 참고.

* Bind ID : bind 의 ID.
* ref : 제약조건을 걸어 놓을 인스턴스의 경로
* 속성 : 제약조건.  

    ref 의 값은 '.'\(dot\) 으로 줄여쓸 수 있다.

    예\) . &gt; 1 은 1보다 ref 의 값이 커야한다는 제약조건이 된다.{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<bind id="calcAge" ref="/root/age" constraint=". >= 19"/>
```
{% endcode %}

