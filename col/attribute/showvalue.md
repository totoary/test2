---
description: col 의 type 이 combo 일 때 콤보 리스트에 label 과 value 를 동시에 보이도록 설정하는 속성
---

# showvalue

## DESCRIPTION

_true : label 값과 value 값을 동시에 보임_ false : label 값만 보임

이 속성을 설정하지 않으면 기본으로 false 로 동작한다.

{% hint style="info" %}
showvalue 를 true 로 설정한 경우 focusIndex 는 짝수로 증가하게된다. 이유는 콤보 리스트 상의 label 과 value 를 각각 하나의 아이템으로 생성하기 때문이다.
{% endhint %}

## VALUES

true / false\(default\)

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col editmode="search" ref="a" type="combo" showvalue="true" />
```
{% endcode %}

