---
description: 사용자가 마우스나 키보드를 사용하여 셀을 다중으로 선택할 수 있도록 설정하는 속성이다.
---

# allowselection

## DESCRIPTION

이 속성을 false 로 설정을 해 놓으면 사용자가 마우스로 드래그 하거나 키보드로 Shift + 방향키를 사용하여 선택한 범위를 늘릴수 없도록 한다. 마우스로 드래그를 하면 선택된 셀만이 바뀌고 선택범위는 늘어나지 않는다.

이 속성이 true 로 설정되어 있으면 사용자가 마우스로 드래그를 하거나 키보드로 shift + 방향키를 사용하거나 ctrl 또는 shift + 마우스 클릭 을 사용해서 다중 셀\(또는 행, 열\) 을 선택 할 수 있다. 셀들의 선택방식은 selectionmode 속성을 따른다.

이 속성은 설정하지 않으면 기본으로 true 로 설정이 된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 allowselection 을 동적으로 제어하기 위해서는 allowSelection property 를 사용한다. 

## **VALUES**

* **true\(default\) / false**

## EXAMPLE

{% code title="\[Static \]" %}
```bash
<datagrid id="datagrid1" nodeset="/root/grid" allowselection="true" 
caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" 
rowsep="|" style="left:35px; top:25px; width:350px; height:150px; ">
```
{% endcode %}

