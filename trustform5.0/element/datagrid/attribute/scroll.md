---
description: datagrid 의 스크롤바가 화면에 표시되는 방법을 설정하는 속성이다.
---

# scroll

## DESCRIPTION

datagrid 의 스크롤바가 화면에 표시되는 방법을 설정하는 속성이다. 가로, 세로 스크롤바를 언제 어떻게 표시 할 지 설정 할 수 있다.

overflow 가 scroll 외의 것으로 설정되어 있으면 동작하지 않는다. 

* auto : 셀들이 차지하는 영역에 따라 자동으로 스크롤바를 표시한다.
* vertical : 세로 스크롤바를 무조건 표시한다.
* horizontal : 가로 스크롤바를 무조건 표시한다.
* both : 가로, 세로 스크롤바를 무조건 표시한다.
* autovscroll : 셀들이 차지하는 영역에 따라 자동으로 세로 스크롤바를 표시한다. 가로 스크롤바는 표시 되지 않는다.
* autohscroll : 셀들이 차지하는 영역에 따라 자동으로 가로 스크롤바를 표시한다. 세로 스크롤바는 표시되지 않는다.
* none : 가로, 세로 스크롤바를 무조건 표시하지 않는다. 입력시 너비를 벗어날 경우 자동으로 행변경이 이루워진다.                      

## VALUES

* **auto\(default\) / vertical / horizontal / both / autovscroll / autohscroll / none**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/grid" scroll="horizontal" 
caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" 
rowsep="|" style="left:175px; top:110px; width:220px; height:95px; ">
```
{% endcode %}

