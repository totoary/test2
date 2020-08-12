---
description: 셀 내용의 길이에 따라 행의 높이를 자동으로 조절하도록 설정하는 속성이다.
---

#  autoresize   

## DESCRIPTION

셀 내용의 길이에 따라 행의 높이를 자동으로 조절하도록 설정하는 속성이다.
이 속성이 true 로 설정되어 있을 때 셀의 내용이 셀에 표시될 수 있는 길이보다 길면 자동으로 높이가 늘어나고, 내용이 짧으면 높이가 줄어들게 된다.

셀의 높이가 조정되는 시점은 다음과 같다.
1) 문서가 처음 로딩되는 시점
2) 그리드의 셀에서 사용자 입력이 끝나고 셀이 에디트 상태에서 빠져나오는 시점
3) 사용자가 그리드 열의 넓이를 변경하는 시점
4) datagrid 의 함수 resizeCells() 가 호출되는 시점

이 속성은 설정하지 않으면 기본으로 false 로 설정이 된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 autoresize 를 동적으로 제어하기 위해서는 autoResize property 를 사용한다. 

## **VALUES**

* **true / false(default\)\**

## EXAMPLE

{% code title="\[Static \]" %}
```bash
<datagrid id="datagrid3" nodeset="/root/g" autoresize="true" caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" rowsep="|" style="left:30px; top:225px; width:350px; height:150px; "> 
```
{% endcode %}



