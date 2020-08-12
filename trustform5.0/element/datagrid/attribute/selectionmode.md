---
description: 그리드의 셀들이 선택되는 방식(셀단위, 행단위, 열단위, 또는 리스트 박스처럼 선택)을 설정하는 속성이다.
---

#   selectionmode                     

## DESCRIPTION

- byrow : 행단위로 선택을 한다. ctrl 키를 이용하여 다중행을 선택할 수 없다.
- bycol : 열단위로 선택을 한다.
- listbox : 행단위로 선택을 한다. ctrl 키를 이용하여 다중행을 선택할 수 있다.
- free : 셀단위로 자유롭게 선택하도록 한다.

이 속성이 설정되지 않으면 기본으로 listbox 로 설정한 것과 같이 동작한다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 selectionmode 을 동적으로 제어하기 위해서는 selectionMode property 를 사용한다.                          
   
## VALUES

byrow / bycol / listbox(default) / free  

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid4" nodeset="/root/grid" caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" rowsep="|" selectionmode="free" style="left:40px; top:105px; width:350px; height:150px; ">  
```
{% endcode %}



