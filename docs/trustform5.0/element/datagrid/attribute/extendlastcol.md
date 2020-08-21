---
description: 그리드의 여백이 보이지 않도록 우측 마지막 열의 너비를 확장하도록 설정하는 속성이다.
---

# extendlastcol

## DESCRIPTION

이 속성은 다음과 같이 설정할 수 있다. ㅁscroll : V-Scroll 의 너비를 고려하여 확장한다. 

* scroll : V-Scroll 의 너비를 고려하여 확장한다. 
* noscroll : V-Scroll 의 너비를 고려하지 않고 무조건 그리드의 너비만큼 확장한다.
* false : 기능을 사용하지 않는다.

이 속성을 설정하지 않으면 기본으로 false 로 설정된다.

{% hint style="info" %}
그리드의 크기보다 캡션의 개수가 많거나 캡션의 너비가 클경우에는 그리드의 크기를 늘릴수가 없으므로 그리드의 크기만큼만 캡션을 보여준다.

attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 extendlastcol 을 동적으로 제어하기 위해서는 extendLastCol property 를 사용한다.
{% endhint %}

## VALUES

* **scroll / noscroll / false\(default\)**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid3" nodeset="/root/g" caption="caption1^caption2^caption3" 
colsep="^" extendlastcol="scroll" mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:430px; top:260px; width:350px; height:150px; "> 
```
{% endcode %}



