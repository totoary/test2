---
description: 그리드의 셀 선택시 셀의 background 이미지를 반전시킬지 설정하는 속성이다.
---

# selectimagestyle

## DESCRIPTION

그리드의 셀 선택시 셀의 background 이미지를 반전시킬지 설정하는 속성이다.

그리드의 셀에 이미지가 적용되어 있을 경우 invert 로 설정하면 이미지의 색상이 반전되고, none 으로 설정하면 셀이 선택되어도 이미지의 색상이 변하지 않는다. 

단, focuscolor attribute 가 설정되어 있으면 selectimagestyle 은 무시되고 "none" 으로 설정한 것처럼 동작한다.

적용 우선순위 : focuscolor &gt; selectimagestyle &gt; selectfontcolorstyle

이 속성을 설정하지 않으면 기본으로 invert 로 설정이 되어서 선택된 셀의 배경 이미지 색상이 반전된다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 selectimagestyle 을 동적으로 제어하기 위해서는 selectImageStyle property 를 사용한다.
{% endhint %}

## VALUES

* **none / invert\(default\)**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/grid" caption="caption1^caption2^caption3"
 colsep="^" mergecellsfixedrows="bycolrec" rowsep="|" selectfontcolorstyle="none" 
 style="left:150px; top:50px; width:350px; height:150px; ">
```
{% endcode %}

