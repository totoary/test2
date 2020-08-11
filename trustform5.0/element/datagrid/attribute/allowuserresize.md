---
description: 사용자가 마우스로 행과 열의 크기를 조절할 수 있도록 설정하는 속성이다.
---

#  allowuserresize  

## DESCRIPTION

이 속성이 true 로 설정되어 있을때 마우스를 fixed cell(고정셀) 의 가장자리로 가져가면 마우스 포인터가 크기를 조절하는 포인터로 바뀌고 그 위치에서 드래그를 하여 행 또는 열의 크기를 조절할 수 있다.
이 속성이 false 로 설정되어 있으면 마우스를 fixed cell(고정셀) 의 가장자리로 가지고 가도 마우스 포인터가 바뀌지 않는다.

사용자가 마우스로 행이나 열의 크기를 조절하면 셀의 크기가 변경되기 전에 onbeforeuserresize 이벤트가 발생하고 크기가 조절 된 후에 onafteruserresize 이벤트가 발생한다. 이 이벤트들은 특수한 경우에 열과 행의 크기가 변경되는 것을 방지하거나 다른 용도로 사용될 수 있다.

이 속성은 설정하지 않으면 기본으로 true 로 설정이 된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 allowuserresize 을 동적으로 제어하기 위해서는 allowUserResize property 를 사용한다.      


## **VALUES**

* **true(default\) / false\**

## EXAMPLE

{% code title="\[Static \]" %}
```bash
<datagrid id="datagrid2" nodeset="/root/g" allowuserresize="false" caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" rowheader="seq" rowsep="|" style="left:30px; top:30px; width:350px; height:150px; ">
```
{% endcode %}


