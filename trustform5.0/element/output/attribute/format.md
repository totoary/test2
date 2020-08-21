---
description: output 컨트롤의 포맷을 설정하는 속성이다.
---

# format

## DESCRIPTION

컨트롤에 맵핑되어 있는 인스턴스의 값에는 순수 데이터만이 들어가지만, 컨트롤에 보일 때에는 포맷이 적용되어서 보일수 있는 기능이다. 날짜, 금액 등을 표시할 때 유용하게 쓰인다. \(예 : yyyy-mm-dd 또는 \#,\#\#\# 등\)

위의 값들 말고도 format 사용자가 지정한 포맷을 사용할 수도 있다.

## VALUES

yyyy-mm-dd / hh:nn:ss / \#,\#\#\# / 999999-9999999

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<output id="output1" format="#,###" style="left:75px; top:290px; width:100px; height:20px; "/>
```
{% endcode %}

