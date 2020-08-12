---
description: datagrid 가 print 될 때 가로 scroll 이 없어지면서 가로로 모든 내용이 print 될 지 여부를 정하는 속성이다. 
---

#  removevscroll              

## DESCRIPTION

- true : datagrid 가 print 될 때 세로 scroll 이 없어지면서 세로로 모든 내용이 print 된다. 
- false : 화면에 보이는 대로 print 된다. 
(속성을 설정하지 않으면 기본값은 “false" 이다)

* Datagrid 보다 아래쪽에 있는 컨트롤들도 Datagrid 높이가 높아진 만큼 아래로 이동하여 겹치지 않게 print 된다.              
   
## VALUES

true / false(default)

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid2" nodeset="/root/scrollSample/gridData/bankTransfer" scroll="auto" caption="Bank^Date^Receiver^Amount" colsep="^" colwidth="100, 100, 100, 100" mergecellsfixedrows="bycolrec" rowsep="|" removevscroll="true" style="left:6px; top:8px; width:325px; height:190px; "> 
```
{% endcode %}



