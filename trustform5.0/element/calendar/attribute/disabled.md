---
description: calendar  컨트롤의 disabled(비활성) 상태를 설정하는 속성
---

# disabled

## DESCRIPTION

calendar 컨트롤의 disabled\(비활성\) 상태를 설정하는 속성이다.

컨트롤이 disabled 상태가 되면 모든 UI 에 관련된 이벤트를 받지 못하게 된다 \(UI 이벤트 : mouse, keyboard, scroll, focus/navindex 관련 event\)

{% hint style="info" %}
Attribute 의 disabled 는 단지 컨트롤의 초기 상태를 의미한다.그러므로 스크립트에서 enabled/disabled 를 조작 하려면 disabled property 를 사용 해야 한다.
{% endhint %}

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<calendar id="toCalendar" disabled="true" style="left:375px; top:280px; width:220px; height:150px; "/>
```
{% endcode %}

