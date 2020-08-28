---
description: group 컨트롤을 화면에 표시할 지를 설정하는 속성이다.
---

# visibility

## DESCRIPTION

group 컨트롤이 hidden 이 되면 group 하위의 컨트롤들이 모두 보이지 않게된다.

*visible : radio 컨트롤이 보인다.
*hidden : radio 컨트롤이 보이지 않는다.

이 속성을 설정하지 않으면 기본으로 visible 로 동작한다.

{% hint style="info" %}
Attribute 의 visibility 는 최초 로딩시 group 을 보여줄지 설정하는 속성이므로 visibility 를  스크립트에서 동적으로 제어하기 위해서는 visible property 를 사용해야 한다.
{% endhint %}

## VALUES

visible / hidden

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<group id="group1" visibility="hidden" style="left:129px; top:233px; width:231px; height:168px; /">
```
{% endcode %}

