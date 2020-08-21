---
description: subtotal 시 subtotal 행이 삽입될 위치를 설정하는 속성이다.
---

# subtotalposition

## DESCRIPTION

subtotalposition 을 above 로 설정하면 subtotal 행이 데이터 행들의 상단에 삽입되고 below 로 설정하면 데이터 행들의 하단에 삽입된다.

이 속성을 설정하지 않으면 above 로 설정한 것과 같이 subtotal 행이 데이터 행의 상단에 삽입된다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 subtotalposition 을 동적으로 제어하기 위해서는 subtotalPosition property 를 사용한다.   
{% endhint %}

## VALUES

* **above\(default\) / below**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/g" caption="caption1^caption2^caption3" 
colsep="^" mergecellsfixedrows="bycolrec" rowsep="|" subtotalposition="below" 
style="left:45px; top:35px; width:350px; height:150px; ">
```
{% endcode %}

