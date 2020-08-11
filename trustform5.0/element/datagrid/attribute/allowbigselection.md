---
description: 그리드의 fixed cell 을 클릭해서 전체 셀들을 선택할 수 있도록 설정하는 속성이다.
---

# allowbigselection

## DESCRIPTION

이 속성이 true 로 설정되어 있고 selectionmode 가 bycol 이면 fixed row 부분을 클릭하여 열 전체를 선택할 수 있고, selectionmode 가 byrow 이면 fixed col 부분을 클릭하여 행 전체를 선택할 수 있다. 

또한 allowbigselection 이 true 로 설정되어 있고 첫번째 열이 fixedcol 이면 그리드의 첫번째 행 첫번째      열\(0,0\) 에 위치한 고정된 셀\(fixed cells\)을 클릭하여 모든 행과 열을 선택할 수 있다. 그리드의 fixedcol 속성으로 fixedcol 을 만들거나 rowheader 속성을 설정하면 첫번째 열이 fixedcol 이 된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 allowbigselection 을 동적으로 제어하기 위해서는 allowBigSelection property 를 사용한다. 

## EXAMPLE

{% code title="\[Static \]" %}
```bash
<datagrid id="datagrid1" nodeset="/root/g" allowbigselection="true" 
caption="caption1^caption2^caption3" colsep="^" fixedcols="2" 
mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:50px; top:45px; width:350px; height:150px; ">
```
{% endcode %}

