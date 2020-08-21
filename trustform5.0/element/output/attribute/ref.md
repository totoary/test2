---
description:   output 컨트롤에 맵핑될 인스턴스의 Xpath 경로를 지정하는 속성이다    
---

#   ref                       

## DESCRIPTION

디자이너상에서 인스턴스를 드래그하여 맵핑하면 ref 속성에 설정할 수 있고, 직접 output 컨트롤의 ref 속성에 맵핑할 인스턴스의 경로를 입력하여 설정할 수 있다.

output 컨트롤은 기본적으로 인스턴스가 필수는 아니지만 인스턴스를 맵핑해 놓으면 맵핑된 인스턴스의 값을 화면에 표시한다

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<output id="output1" ref="/root/Basic" style="left:75px; top:290px; width:100px; height:20px; "/> 
```
{% endcode %}
