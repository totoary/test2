---
description: datagrid 가 print 될 때 세로 scroll 이 없어지면서 세로로 모든 내용이 print 될 지 여부를 정하는 속성이다.
---

# removehscroll

## DESCRIPTION

Datagrid 보다 우측에 있는 컨트롤들도 Datagrid 의 너비가 넓어진 만큼 우측으로 이동하여 겹치지 않게 print 된다.

* true : datagrid 가 print 될 때 가로 scroll 이 없어지면서 가로로 모든 내용이 print 된다. 
* false : 화면에 보이는 대로 print 된다. \(속성을 설정하지 않으면 기본값은 “false" 이다\)

## VALUES

* **true / false\(default\)**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid3" nodeset="/root/scrollSample/gridData/bankTransfer" 
scroll="auto" caption="Bank^Date^Receiver^Amount" colsep="^" colwidth="100, 100, 
100, 100" mergecellsfixedrows="bycolrec" rowsep="|" removehscroll="true" 
style="left:6px; top:8px; width:325px; height:190px; ">
```
{% endcode %}

