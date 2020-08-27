---
description: textarea 컨트롤의 disabled(비활성) 상태를 설정하는 속성
---

# disabled

## DESCRIPTION

<textarea id="textarea1" bind="textareaBind" class="textareaClass" style="left:35px; top:60px; width:250px; height:240px; ">  컨트롤의 disabled\(비활성\) 상태를 설정하는 속성이다.

컨트롤이 disabled 상태가 되면 모든 UI 에 관련된 이벤트를 받지 못하게 된다 \(UI 이벤트 : mouse, keyboard, scroll, focus/navindex 관련 event\)

이 속성을 설정하지 않으면 기본으로 false 로 설정한 것과 같이 활성화가 된다.

{% hint style="info" %}
Attribute 의 disabled 은 단지 컨트롤의 초기 상태를 의미한다. 그러므로 스크립트에서 enabled/disabled 를 조작 하려면 disabled property 를 사용해야 한다.
{% endhint %}

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<textarea id="textarea1" bind="textareaBind" disabled="true" style="left:35px; top:60px; width:250px; height:240px; "> 
```
{% endcode %}

