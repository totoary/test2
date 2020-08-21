<<<<<<< HEAD
---
description: 지정된 컨트롤에 접근하기 위한 단축키를 설정할 수 있다.
---

# accesskey

## DESCRIPTION

기본적으로 accesskey 속성에 지정한 키를 누르면 해당 컨트롤에 onaccesskey 이벤트와 DOMActivate 이벤트가 순차적으로 발생한다.

형식 : \[namedkey \| keycode\(\)\] + …

이 속성은 설정하지 않으면 accesskey 는 설정되지 않는다.

{% hint style="info" %}
* named key insert, delete, home, pageup, pagedown, end, backspace, pause, print, enter, tab, escape, up, down, left, right, ctrl, alt, shift f1..f12, 0..9, a..z \(a..z 는 대소문자 구분없이 사용하고, alt 키는 지원하지 않는다\)
* keycode function keycode\(code\) : 주의 keycode\(\) 에서 keycode 와 \( 를 붙여 써야한다.
{% endhint %}

## VALUES

f1 / f2 / ctrl+f1 / shift+f2 / ctrl+keyCode\(20\) / ctrl+enter /

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="input1" ref="/root/test" accesskey="ctrl+e" 
style="left:50px; top:215px; width:100px; height:20px; "> 
```
{% endcode %}

=======
---
description: 지정된 컨트롤에 접근하기 위한 단축키를 설정할 수 있다.
---

# accesskey

## DESCRIPTION

기본적으로 accesskey 속성에 지정한 키를 누르면 해당 컨트롤에 onaccesskey 이벤트와 DOMActivate 이벤트가 순차적으로 발생한다.

형식 : \[namedkey \| keycode\(\)\] + …

이 속성은 설정하지 않으면 accesskey 는 설정되지 않는다.

{% hint style="info" %}
* named key insert, delete, home, pageup, pagedown, end, backspace, pause, print, enter, tab, escape, up, down, left, right, ctrl, alt, shift f1..f12, 0..9, a..z \(a..z 는 대소문자 구분없이 사용하고, alt 키는 지원하지 않는다\)
* keycode function keycode\(code\) : 주의 keycode\(\) 에서 keycode 와 \( 를 붙여 써야한다.
{% endhint %}

## VALUES

f1 / f2 / ctrl+f1 / shift+f2 / ctrl+keyCode\(20\) / ctrl+enter /

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="input1" ref="/root/test" accesskey="ctrl+e" 
style="left:50px; top:215px; width:100px; height:20px; "> 
```
{% endcode %}

>>>>>>> eaecbff44ad16a728baa64cf76485a2e44cd3f57
