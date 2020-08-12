---
description: 그리드의 데이터 행들 중 최상위에 위치할 세로 스크롤이 되지 않는 frozen row 의 갯수를 설정하는 속성이다.
---

# frozenrows 

## DESCRIPTION

그리드의 데이터 행들 중 최상위에 위치할 세로 스크롤이 되지 않는 frozen row 의 갯수를 설정하는 속성이다.
frozen row 안의 셀들은 선택되고 수정될 수 있으나, 사용자가 세로 스크롤을 움직였을 때 스크롤 되지 않고 항상 그리드의 상단에서 이동하지 않는다.
frozen row 는 그리드에 행이 많을 때 특정 행을 고정시켜서 보여줄 때 이용하면 편리하다.
backcolorfrozen 과 forecolorfrozen 속성을 사용하여 그리드 안에서 Frozen 된 부분의 바탕이나 글꼴색을 지정할 수 있다.

이 속성을 설정하지 않으면 기본으로 frozen row 는 나타나지 않는다.

* 만약 스크롤이 존재하는 datagrid 에서 마지막 row 까지 frozenrows 속성을 설정하게 되면 전체 row 가 frozen 이 되면서 스크롤을 움직이면 row 들도 움직이게 된다. 

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 frozenrows 를 동적으로 제어하기 위해서는 frozenRows property 를 사용한다.   

## VALUES



## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/Example/datagridInformation/item" caption="caption1^caption2^caption3^caption4" colsep="^" colwidth="100, 100, 100, 100" forecolorfrozen="#3366ff" frozenrows="1" mergecellsfixedrows="bycolrec" rowsep="|" style="left:70px; top:60px; width:385px; height:265px; "> 
```
{% endcode %}



