---
description: 그리드의 frozen cell 의 텍스트 색상을 설정하는 속성이다.
---

# forecolorfrozen

## DESCRIPTION

이 속성에 색상 코드를 설정해 주면 frozen cell 들의 텍스트 색상이 설정된 색상으로 바뀐다. frozen cell 들은 frozen rows 와 frozen cols 를 모두 의미한다.

이 속성을 설정하지 않으면 frozen cell 들의 텍스트 색상은 기본으로 검정색이 된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 forecolorfrozen 을 동적으로 제어하기 위해서는 foreColorFrozen property 를 사용한다.   

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/Example/datagridInformation/item" 
caption="caption1^caption2^caption3^caption4" colsep="^" colwidth="100, 100, 100, 
100" forecolorfrozen="#3366ff" frozenbottomrows="1" mergecellsfixedrows="bycolrec" 
rowsep="|" style="left:70px; top:60px; width:465px; height:265px; ">
```
{% endcode %}

