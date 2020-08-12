---
description: 그리드의 셀 선택시 셀의 background 이미지를 반전시킬지 설정하는 속성이다.
---

# selectfontcolorstyle

## DESCRIPTION

그리드의 셀에 이미지가 적용되어 있을 경우 invert 로 설정하면 이미지의 색상이 반전되고, none 으로 설정하면 셀이 선택되어도 이미지의 색상이 변하지 않는다. 

단, focuscolor attribute 가 설정되어 있으면 selectimagestyle 은 무시되고 "none" 으로 설정한 것처럼 동작한다.

적용 우선순위 : focuscolor &gt; selectimagestyle &gt; selectfontcolorstyle

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 selectimagestyle 을 동적으로 제어하기 위해서는 selectImageStyle property 를 사용한다.                         
{% endhint %}

## VALUES

* **none / invert\(default\)**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid2" nodeset="/root/grid" caption="caption1^caption2^caption3"
 colsep="^" selectimagestyle="none" mergecellsfixedrows="bycolrec" rowsep="|" 
 style="left:390px; top:225px; width:350px; height:150px; ">
```
{% endcode %}

