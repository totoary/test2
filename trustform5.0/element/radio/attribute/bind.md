---
description: checkbox 컨트롤과 연동할 bind 의 id 를 지정하는 속성     
---

#   bind                       

## DESCRIPTION

bind 를 사용하면 calculate, constraint 등 편리한 기능을 사용할 수 있다.  
bind를 checkbox 에 연결시키면 사용하면 집적 checkbox에 인스턴스를 맵핑하는 것이 아니라 
checkbox에 맵핑된 bind 의 ref 에 설정된 XPath 경로에 있는 인스턴스가 checkbx 에 맵핑된 인스턴스의 역할을 한다.
이 속성은 설정하지 않으면 bind는 설정이 되지 않는다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="checkbox1" bind="bind1" overflow="visible" appearance="full" style="left:50px; top:280px; width:125px; height:135px; border-style:none; ">
```
{% endcode %}