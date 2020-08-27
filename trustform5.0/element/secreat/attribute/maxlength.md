---
description: secret 컨트롤에 입력 가능한 최대 자리 수를 설정하는 속성이다.
---

# maxlength

## DESCRIPTION

maxlength 를 지정하면 maxlength 만큼 값이 입력되고, 다음 컨트롤로 포커스가 이동한다.

입력 가능한 최대 byte 수를 설정하기 때문에 숫자나 영문 입력시 정상동작 한다. (한글은 byte 수가 다르기 때문에 예상치 않은 동작이 발생할 수 있다.)

{% hint style="info" %}
최대 글자수가 넘어갈 때 "onmaxlength" 이벤트가 발생한다. 
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<secret id="secret1" ref="/root/Basic" imemode="disabled" maxlength="5" style="left:480px; top:260px; width:100px; height:20px; "/> 
```
{% endcode %}

