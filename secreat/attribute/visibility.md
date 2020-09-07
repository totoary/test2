---
description: secret  컨트롤을 화면에 표시할 지를 설정하는 속성이다.
---

# visibility

## DESCRIPTION

_visible : secret  컨트롤이 보인다.
_ hidden : secret  컨트롤이 보이지 않는다.

visibility 속성의 기본값은 visible 이다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 visibility 를 동적으로 제어하기 위해서는 visible property 를 사용해야 한다.
{% endhint %}

## VALUES

visible / hidden

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<secret id="secret1" ref="/root/Basic" visibility="hidden" imemode="disabled" style="left:395px; top:215px; width:100px; height:20px; "/> 
```
{% endcode %}

