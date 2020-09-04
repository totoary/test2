---
description: datagrid 캡션 행들의 높이를 특정 높이로 설정할 때 사용되는 속성이다.
---

# rowheight

## DESCRIPTION

첫번째 캡션 행부터 각 캡션 행의 높이를 지정할 수 있다. 구분자는 쉼표\(,\) 로 표시하고 첫 행부터 순서대로 지정한다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 rowheight 를 동적으로 제어하기 위해서는 rowHeight property 를 사용한다.

구분자 쉼표\(,\)를 넣어서 캡션 뿐만 아니라 데이터까지 rowheight 를 줄 수 있다. 이 때 첫번째 값부터 캡션을 포함하여 행들의 rowheight 가 차례대로 설정된다.
{% endhint %}

## VALUES

* **seq / reverseseq / select / update**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/grid" caption="caption1^caption2^caption3|
caption1-1^caption2-1^caption3-1" colsep="^" mergecellsfixedrows="bycolrec" 
rowheight="30,40" rowsep="|" style="left:50px; top:30px; width:350px; 
height:150px; ">
```
{% endcode %}

