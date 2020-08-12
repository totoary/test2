---
description: 그리드의 하단에 위치할 세로 스크롤이 되지 않는 frozen row 의 갯수를 설정하는 속성이다.
---

# frozenbottomrows

## DESCRIPTION

frozenrows 는 그리드의 상단에 frozen row 를 설정하는 반면 frozenbottomrows 는 그리드의 하단에 frozen row 를 설정하는 차이점이 있다. frozen row 안에 있는 셀들은 선택되고 수정될 수 있으나, 사용자가 세로 스크롤을 움직였을 때 스크롤 되지 않고 항상 그리드의 최하단에서 이동하지 않는다.

backcolorfrozen 과 forecolorfrozen 속성을 사용하여 그리드 안에서 frozen 된 부분의 바탕이나 글꼴색을 지정할 수 있다.

이 속성을 설정하지 않으면 기본으로 frozen row 는 나타나지 않는다.

* 스크롤이 존재하는 그리드에 frozenbottomrow 를 설정하였을 때, frozen 된 bottomrow 는 그리드의 마지막 행 데이터이기 때문에 마우스 드래그로 다중선택 시 스크롤이 움직이지 않고, frozenbottomrow 행이 선택되는 등의 사용자가 의도하지 않은 동작을 막기 위해서 다중 선택 시 frozenbottomrow 는 다중선택이 안 되도록 하였고, 다중 선택이 되도록 하기 위해서는 ctrl 키를 사용하면 가능하다.
* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 frozenbottomrows 를 동적으로 제어하기 위해서는 frozenBottomRows property 를 사용한다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/Example/datagridInformation/item" 
caption="caption1^caption2^caption3^caption4" colsep="^" colwidth="100, 100, 100, 
100" forecolorfrozen="#3366ff" frozenbottomrows="1" mergecellsfixedrows="
bycolrec" rowsep="|" style="left:70px; top:60px; width:465px; height:265px; ">
```
{% endcode %}

