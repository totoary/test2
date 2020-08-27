---
description: roundmode 를 적용할 위치를 설정하는 속성이다.
---

# roundposition

## DESCRIPTION

roundmode 를 설정한 상태에서 어느 자리에서 roundmode 를 적용 할 것인지를 설정하는 것이다. 

이 속성에서 양수를 설정하면 정수부의 자리 수를 의미하고, 음수를 설정하면 소수부의 자리 수를 의미한다. 

\(예 : 2 는 정수 2번째 자리, 즉 10의 자리에서 roundmode 를 적용시킨다는 의미이고, -2 는 소수 2번째 자리에서 적용시킨다는 의미이다.\)

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<caption id="roundCaption" ref="/root/roundValue" format="#.#" roundmode="round" roundposition="-2" style="left:225px; top:125px; width:100px; height:20px; "> 
```
{% endcode %}

