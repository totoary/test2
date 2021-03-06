---
description: 지정된 컨트롤에 접근하기 위한 단축키를 설정할 수 있다.
---

# accesskey

## DESCRIPTION

기본적으로 accesskey 속성은 컨트롤에 onaccesskey 이벤트 발생 후 DOMActivate 이벤트를 Dispatch 한다.

형식 : \[namedkey \| keycode\(\)\] + …

이 속성은 설정하지 않으면 accesskey 는 설정되지 않는다.

{% hint style="info" %}
* named key insert, delete, home, pageup, pagedown, end, backspace, pause, print, enter, tab, escape, up, down, left, right, ctrl, alt, shift f1..f12, 0..9, a..z \(a..z 는 대소문자 구분없이 사용하고, alt 키는 지원하지 않는다\)
* keycode function keycode\(code\) : 주의 keycode\(\) 에서 keycode 와 \( 를 붙여 써야한다.
{% endhint %}

## VALUES

f1 / f2 / ctrl+f1 / shift+f2 / ctrl+keyCode\(20\) / ctrl+enter /

&lt;&lt;&lt;&lt;&lt;&lt;&lt; HEAD

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="doing" ref="/root/selected" accesskey="ctrl+a" overflow="scroll" 
appearance="compact" style="left:340px; top:265px; width:135px; height:150px; 
font-weight:bold; background-color:#ffff99; ">
```
{% endcode %}

