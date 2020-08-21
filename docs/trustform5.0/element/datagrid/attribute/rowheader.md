---
description: 그리드의 가장 첫번째 열에 fixedcol 을 추가하고 각 행의 상태를 표시하도록 설정하는 속성이다.
---

# rowheader

## DESCRIPTION

추가된 fixed col 에는 순번, 선택된 행의 표시, Multi Update 상태표시 등의 기능을 할 수 있다.

설정될 수 있는 옵션들은 다음과 같다.

* seq : 각 행에 순번을 붙여 준다.
* reverseseq : 각 행에 순번을 역순으로 붙여 준다.
* select : 선택된 행에 선택 표시를 붙여준다.
* update : 각 행에 Multi Update 상태의 표시를 붙여준다.                

## VALUES

* **seq / reverseseq / select / update**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/grid" caption="caption1^caption2^caption3"
 colsep="^" mergecellsfixedrows="bycolrec" rowheader="seq" rowsep="|" 
 style="left:50px; top:30px; width:350px; height:150px; ">
```
{% endcode %}

