---
description: 그리드의 데이터 셀 영역에서 짝수번호 행에만 바탕색상을 설정하는 속성이다.
---

# backcoloralternate

## DESCRIPTION

이 속성에 색상을 지정해 주면 그리드의 데이터 구간에서 짝수 행의 바탕색\(background-color\) 가 지정된 색으로 표현이 된다. 데이터가 많을 때 알아보기 편하고, 디자인 효과를 적용할 때 유용하다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 backcoloralternate 를 동적으로 제어하기 위해서는 backColorAlternate property 를 사용한다. 
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid4" nodeset="/root/g" backcoloralternate="#00ffff" 
caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" 
rowsep="|" style="left:80px; top:445px; width:350px; height:150px; ">
```
{% endcode %}

