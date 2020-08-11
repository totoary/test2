
---
description: 그리드의 frozen cell 의 바탕색을 설정하는 속성이다
---

# backcolorfrozen 

## DESCRIPTION

이 속성에 색상 코드를 설정해 주면 frozen cell 들의 배경색상이 설정된 색상으로 변경된다.
frozen cell 들은 frozen rows 와 frozen cols 를 모두 의미한다.

이 속성을 설정하지 않으면 frozen cell 들의 바탕색상은 기본으로 흰색이 된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 backcolorfrozen 을 동적으로 제어하기 위해서는 backColorFrozen property 를 사용한다.  

## EXAMPLE

{% code title="\[Static \]" %}
```bash
<datagrid id="datagrid2" nodeset="/root/grid" backcolorfrozen="#ccffff" 
caption="caption1^caption2^caption3" colsep="^" frozencols="1" frozenrows="2" 
mergecellsfixedrows="bycolrec" rowsep="|" style="left:40px; top:45px; width:290px; height:150px; ">
```
{% endcode %}

