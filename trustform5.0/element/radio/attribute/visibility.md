---
description: radio 컨트롤을 화면에 표시할 지를 설정하는 속성이다.
---

# visibility

## DESCRIPTION

_visible : radio 컨트롤이 보인다._ hidden : radio 컨트롤이 보이지 않는다.

이 속성을 설정하지 않으면 기본으로 visible 로 동작한다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 visibility 를 동적으로 제어하기 위해서는 visible property 를 사용해야 한다.
{% endhint %}

## VALUES

visible / hidden

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="nationRadio" ref="/root/country" visibility="hidden" overflow="visible" 
appearance="full" cols="4" style="left:40px; top:340px; width:340px; height:215px; 
border-style:none; ">
```
{% endcode %}

