---
description: 그리드의 입력 값에 대해 validation 체크를 할지 여부를 설정하는 속성 
---

# validateformat 

## DESCRIPTION

col 에 format 이 설정되어 있는 경우 이 속성이 true 이면 입력된 값이 format 에 맞는 값인지 validation 체크를 수행합니다.

Validation 체크 직전에 onbeforevalidation 이벤트를 발생하고,
Valid 상태 이면 onvalidformat 이벤트를 발생하고,
Invalid 상태 이면 oninvalidformat 이벤트를 발생시킨다.

onvalidformat 과 oninvalidformat 이벤트들은 validateformat attribute 가 true 로 설정되어 있을 때에만 발생한다.

이 속성은 설정하지 않으면 false 로 설정한 것과 같이 validation 체크를 하지 않는다.   

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col ref="data" type="input" format="99-99" validateformat="true"/> 
```
{% endcode %}
