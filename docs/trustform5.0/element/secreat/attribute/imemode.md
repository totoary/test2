---
description: secret 컨트롤의 imemode를 설정하는 속성이다.
---

# imemode

## DESCRIPTION

imemode 를 설정한 다음 secret 컨트롤에 포커스가 갔을 때 영문 또는 한글이 입력 되도록 설정할 수 있다.

{% hint style="info" %}디자이너에서 secret 컨트롤 생성시 기본적으로 imemode = "disabled"가 설정되고, 컨트롤 생성한 후 imemode 설정을 변경할 수 있다.{% endhint %}

설정 값은 다음과 같다. (secret 의 기본설정은 disabled) 

* auto : 기존의 imemode 상태를 유지한다. imemode 설정이 되어 있지 않은것처럼 동작할 때 사용한다.
* disabled : 한글이 입력되지 않고, 영문과 숫자가 입력이 된다.
* alpha : 영문으로 입력이 시작되고, 한영키로 한글을 입력할 수 있다.
* hangul : 한글으로 입력이 시작되고, 한영키로 영문을 입력 할 수 있다      

## VALUES

auto / disabled / alpha / hangul

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<secret id="secret1" ref="/root/basic" imemode="disabled" style="left:360px; top:220px; width:100px; height:20px; "/> 
```
{% endcode %}

