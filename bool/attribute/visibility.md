---
description: bool 컨트롤을 화면에 표시할 지를 설정하는 속성이다.
---

# visibility

## DESCRIPTION

_visible : bool 컨트롤이 보인다._ hidden : bool 컨트롤이 보이지 않는다.

{% hint style="info" %}
Attribute 의 visibility 는 최초 로딩 시 bool 컨트롤을 보여줄지를 설정하는 속성이므로 visibility 를 스크립트에서 동적으로 제어하기 위해서는 visible property 를 사용해야 한다.
{% endhint %}

## VALUES

visible / hidden

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<bool id="bool1" visibility="hidden" ref="/root/a" style="left:345px; top:60px; width:100px; height:20px; "/>
```
{% endcode %}

