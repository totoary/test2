---
description: import 컨트롤을 초기 화면에 표시할 지를 설정하는 속성이다.
---

# visibility

## DESCRIPTION

* visible : import 컨트롤이 보인다.
* hidden : import 컨트롤이 보이지 않는다.

이 속성을 설정하지 않으면 기본으로 visible 로 동작한다.

{% hint style="info" %}
Attribute 의 visibility 는 최초 로딩시 import 를 보여줄지 설정하는 속성이므로 visibility 를 스크립트에서 동적으로 제어하기 위해서는 visible property 를 사용해야 한다.
{% endhint %}

## VALUES

visible / hidden

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<import id="import2" visibility="hidden" src="visible_bind.xrw" 
style="left:30px; top:215px; width:540px; height:320px; "/>
```
{% endcode %}

