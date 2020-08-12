---
description: 그리드의 subtotal 기능을 사용할 때 multitotal 기능을 사용하도록 설정하는 속성이다.
---

# multitotal

## DESCRIPTION

multitotal 을 true 로 설정하면 subtotal 을 여러번 수행할 때 그룹 열이 같고 계산 열이 다를 경우 하나의 subtotal 행에 모든 결과값을 표시해 준다. 

multitotal 을 false 로 설정하면 subtotal 을 여러번 수행할 경우 항상 새로운 subtotal 행을 만든다.

그리드 subtotal 기능의 자세한 내용은 TrustForm5.0 가이드 &gt; 컨트롤 &gt; grid 컨트롤 &gt; grid 컨트롤 부분 합계 구하기 참고.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 multitotal 을 동적으로 제어하기 위해서는 multiTotal property 를 사용한다.
{% endhint %}

## VALUES

* **true\(default\) / false**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/g" caption="caption1^caption2^caption3^
caption4" colsep="^" colwidth="100, 100, 100, 100" mergecellsfixedrows="bycolrec" 
multitotal="true" rowsep="|" 
style="left:30px; top:35px; width:430px; height:225px; ">
```
{% endcode %}

