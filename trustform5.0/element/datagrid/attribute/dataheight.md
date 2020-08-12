---
description: 그리드의 caption 행을 제외한 데이터 행들의 높이 값을 설정하는 속성이다.
---

# dataheight



그리드의 caption 행을 제외한 데이터 행들의 높이 값을 설정하는 속성이다. 데이터 행들이 특정 높이로 보여져야 할 경우에 유용하다. 이 속성이 설정되지 않으면 기본 높이로 나타나게 된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 dataheight 를 동적으로 제어하기 위해서는 dataHeight property 를 사용한다.  



{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/g" caption="caption1^caption2^caption3" 
colsep="^" dataheight="30" mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:50px; top:35px; width:350px; height:150px; "> 
```
{% endcode %}

