---
description: 그리드 각 열의 너비를 설정하는 속성이다.
---

# colwidth



열의 순서대로 나열하며 구분자는 쉼표\(,\) 로 표시한다. 그리드의 열들 중 visibility 속성이 hidden 으로 설정되어 있는 열들의 너비도 명시되어야 한다.

이 속성은 직접 설정하지 않아도 디자이너에서 그리드의 열의 너비를 마우스로 조정하면 자동으로 입력이 된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 colwidth 를 동적으로 제어하기 위해서는 colWidth property 를 사용한다.   

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/g" 
caption="caption1^caption2^caption3^caption4" colsep="^" 
colwidth="100, 100, 50, 100" mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:65px; top:50px; width:460px; height:150px; ">                                                          
```
{% endcode %}

