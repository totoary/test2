---
description: null
---

# maxlength

## DESCRIPTION

input 컨트롤에 입력 가능한 최대 자리 수를 설정하는 속성이다. maxlength 를 지정하면 maxlength 만큼 값이 입력되고, 다음 컨트롤로 포커스가 이동한다.

입력 가능한 최대 byte 수를 설정하기 때문에 숫자나 영문 입력시 정상동작 한다. \(한글은 byte 수가 다르기 때문에 예상치 않은 동작이 발생할 수 있다.\)

{% hint style="info" %}
최대 자리수가 넘어갈 때 "onmaxlength" 이벤트가 발생한다. format 이 적용된 경우에는 format 의 길이만큼 maxlength 가 설정되어 있어야 한다는 제약이 있다.

mask = include 가 설정되어 있고, maxlenth 가 설정되어 있는경우 값 입력 시 설정된 format 의 포맷문자도 maxlength 길이로 체크된다.

maxlength 체크는 인스턴스값을 가지고 체크를 해주기 때문에 mask = include 가 설정되어 있을 때는 format 을 고려하여 maxlength 를 설정해 주어야한다.
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="input1" maxlength="10" autonext="true"style="left:75px; top:90px; width:100px; height:20px; "/>
```
{% endcode %}

