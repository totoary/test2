---
description:treeview 컨트롤에 bind 를 지정할 때 사용하는 속성이다.
---

#  bind 

## DESCRIPTION
bind 를 사용하면 calculate, constraint 등 편리한 기능을 사용할 수 있다.

bind 를 treeview 에 연결시켜서 사용하면 집적 treeview 에 인스턴스를 맵핑하는 것이 아니라 treeview 에 맵핑된 bind 의 ref 에 설정된 XPath 의 경로에 있는 인스턴스가 
treeview 에 맵핑된 인스턴스의 역할을 한다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<treeview id="empolyeeTree" bind="checkpass" expanddepth="1" style="left:55px; top:250px; width:195px; height:190px; font-weight:bold; background-color:#e3f30b; "> 
```
{% endcode %}
