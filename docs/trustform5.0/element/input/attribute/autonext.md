---
description: maxlength 만큼 입력이 되고 다음 컨트롤로 포커스가 이동하도록 설정하는 속성
---

# autonext

## DESCRIPTION

input 컨트롤의 maxlength attribute 또는 format attribute 와 같이 길이에 제한을 두는 속성을 설정했을 때 최대 길이만큼 입력이 되면, 자동으로 다음 셀로 포커스를 이동시켜주는 속성이다.

maxlength 를 지정하고 autonext 를 설정하면 maxlength 만큼 값이 입력 되고, 다음 컨트롤로 포커스가 이동한다. 예를 들어, maxlength 속성을 5로 설정했을 경우에는 5자리를 입력하면 다음셀로 포커스가 이동한다. 또는 format 속성을 '9999' 와 같이 설정하면 4자리의 숫자를 입력 한 후에 포커스가 자동으로 다음 컨트롤로 이동한다.

이 속성은 설정하지 않으면 기본으로 true 로 설정한 것처럼 동작한다.

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="input1" autonext="true" format="hh:nn:ss style="left:75px; top:90px; width:100px; height:20px; "/>
```
{% endcode %}

