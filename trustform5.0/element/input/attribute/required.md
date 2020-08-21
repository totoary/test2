---
description: input 컨트롤에 required 이벤트에 대한 설정을 지정하는 속성이다.
---

# required

## DESCRIPTION

input 컨트롤에 required 이벤트에 대한 설정을 지정하는 속성이다. required 속성을 true 로 설정하면 input 컨트롤에 사용자가 입력값을 변경하거나 model.refresh\(\) 되는 시점마다 xforms-required 이벤트를 발생시키고, 속성을 false 로 설정하면 xforms-optional 이벤트를 발생시킨다.

submission을 수행할 때, required = true 설정 시 값이 없으면 xforms-required-error 이벤트가 발생하면서 ubmission 을 수행하지 않는다. false 로 설정하면 값이 없어도 submission을 수행한다.

* true : xforms-required 이벤트
* false : xforms-optional 이벤트   

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="input1" ref="/root/res" maxlength="20" required="true" style="left:45px; top:50px; width:100px; height:25px; ">
```
{% endcode %}

