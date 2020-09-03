---
description: textarea 컨트롤의 imemode를 설정하는 속성이다.
---

# imemode

## DESCRIPTION

imemode 를 설정한 다음 input 컨트롤에 포커스가 갔을 때 영문 또는 한글이 입력 되도록 설정할 수 있다.

* disabled : 한글이 입력되지 않고, 영문과 숫자가 입력이 된다.
* alpha : 영문으로 입력이 시작되고, 한영키로 한글을 입력할 수 있다.
* hangul : 한글으로 입력이 시작되고, 한영키로 영문을 입력 할 수 있다.   

## VALUES

disabled / alpha / hangul

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<textarea id="textarea1" ref="/root/from" imemode="disabled" style="left:30px; top:25px; width:220px; height:205px; "/>
```
{% endcode %}

