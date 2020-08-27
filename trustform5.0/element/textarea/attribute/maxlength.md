---
description: 입력 가능한 최대 자리 수를 설정하는 속성 
---

# maxlength

## DESCRIPTION

textarea 컨트롤에 입력 가능한 최대 자리 수를 설정하는 속성이다. maxlength 를 지정하면 maxlength 만큼 값이 입력되고, 다음 컨트롤로 포커스가 이동한다.

{% hint style="info" %}
최대 글자수가 넘어갈 때 "onmaxlength" 이벤트가 발생한다. 
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<textarea id="textarea1" ref="/root/from" imemode="disabled" maxlength="200" style="left:30px; top:25px; width:220px; height:205px; "/> 
```
{% endcode %}

