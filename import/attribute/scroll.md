---
description: 'import 의 스크롤바가 화면에 표시되는 방법을 설정하는 속성이다. 가로, 세로 스크롤바를 언제 어떻게 표시 할 지 설정 할 수 있다.'
---

# scroll

## DESCRIPTION

가로, 세로 스크롤바를 언제 어떻게 표시 할 지 설정 할 수 있다.

* auto : 컨트롤들이 차지하는 영역에 따라 자동으로 스크롤바를 표시한다.
* vertical : 세로 스크롤바를 무조건 표시한다.
* horizontal : 가로 스크롤바를 무조건 표시한다.
* both : 가로, 세로 스크롤바를 무조건 표시한다.
* autovscroll : 컨트롤들이 차지하는 영역에 따라 자동으로 세로 스크롤바를 표시한다. 가로 스크롤바는 표시 되지 않는다.
* autohscroll : 컨트롤들이 차지하는 영역에 따라 자동으로 가로 스크롤바를 표시한다. 세로 스크롤바는 표시되지 않는다.
* none : 가로, 세로 스크롤바를 무조건 표시하지 않는다. 입력시 너비를 벗어날 경우 자동으로 행변경이 이루워진다.

이 속성을 설정하지 않으면 기본으로 auto 가 설정된다.

{% hint style="info" %}
overflow 속성이 scroll 값으로 설정되어 있어야 정상적으로 동작한다.
{% endhint %}

## VALUES

auto / vertical / horizontal / both / autovscroll / autohscroll

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<import id="import1" overflow="scroll" scroll="both" src="sample.xrw" 
style="left:145px; top:135px; width:200px; height:150px; "/>
```
{% endcode %}

