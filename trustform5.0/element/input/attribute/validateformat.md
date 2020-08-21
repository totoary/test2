---
description: input 컨트롤의 입력값에 대해 validation 체크를 할 지 여부를 설정하는 속성이다.   
---

#  validateformat                         

## DESCRIPTION

input 컨트롤에 format 이 설정되어 있는 경우 이 속성이 true 이면 입력된 값이 format 에 맞는 값인지 validation 체크를 수행한다.

Validation 체크 직전에 onbeforevalidation 이벤트를 발생하고, valid 상태이면 onvalidformat 이벤트를 발생하며, 
Invalid 상태이면 oninvalidformat 이벤트를 발생시킨다.

onvalidformat 과 oninvalidformat 이벤트들은 validateformat attribute 가 true 로 설정되어 있을 때에만 발생한다.

이 속성은 설정하지 않으면 false 로 설정한 것과 같이 validation 체크를 하지 않는다. 

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="input1" format="yyyy/mm/dd" style="left:20px; top:210px; width:100px; height:20px; ">
      <script type="javascript" ev:event="onvalidformat">
                  alert('onvalidformat');
      </script>
      <script type="javascript" ev:event="oninvalidformat">
                  alert('oninvalidformat');
      </script>
</input> 
```
{% endcode %}