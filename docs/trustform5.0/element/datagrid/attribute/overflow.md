---
description: datagrid 가 자식 셀들이 차지하는 영역에 대한 표현 방법을 설정하는 속성이다.
---

# overflow

## DESCRIPTION

이 속성을 설정하지 않으면 기본으로 scroll 로 설정한 것과 같이 동작한다.

* visible : 모든 셀들이 화면에 표시될 수 있도록 datagrid 의 영역을 확장하거나 축소한다.
* hidden : 자식 셀들이 datagrid 의 영역을 벗어나면 영역을 벗어난 셀들은 화면에 보이지 않도록 한다.
* scroll : 자식 셀들이 body 의 영역을 벗어나면 스크롤바를 보여준다.

## VALUES

* **visible / hidden / scroll\(default\)**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/grid" overflow="visible" 
caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" 
rowsep="|" style="left:35px; top:60px; width:350px; height:150px; ">
```
{% endcode %}

