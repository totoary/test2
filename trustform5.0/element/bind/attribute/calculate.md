---
description: 여러 값을 참조하여 값을 계산하는 속성
---

# calculate

## DESCRIPTION

여러 값을 참조하여 어떠한 값을 계산하거나 어떠한 값이 다른 값에 의존할 때 유용하게 사용할 수 있다.

bind 창을 통해서 생성시 참고.

* Bind ID : bind 의 ID.
* ref : 수식을 통해 나온 결과값을 저장할 인스턴스 경로.
* 속성 : 자신이 계산하고자 하는 수식.

  \(속성 창의 수식을 통해서 나온 결과값이 ref 경로의 인스턴스에 저장된다.\)

## EXAMPLE

{% code title="\[Dynamic\]" %}
```markup
script type="javascript" ev:event="DOMActivate">
    <![CDATA[ 
        bind1.attribute( "calculate" ) = "/root/a * /root/b";
    ]]>
</script>
```
{% endcode %}

