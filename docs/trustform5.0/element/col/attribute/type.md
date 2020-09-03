---
description: 열의 형식을 설정하는 속성이다.
---

# type

## DESCRIPTION

이 속성의 설정에 따라 그리드의 열을 combo, checkbox 등으로 사용할 수 있다.
이 속성을 설정하지 않으면 그리드의 열이 기본으로 output 으로 사용된다.

{% hint style="info" %}
이 속성을 inputdate 로 설정하였을 때 버튼을 클릭하면 onbuttonclick 이벤트가 내부적으로 발생한 이후에 Calendar 를 띄운다.   
{% endhint %}

## VALUES

output / input / inputbutton / inputdate / combo / checkbox / radio

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col ref="idNumber" type="input"/> 
```
{% endcode %}
