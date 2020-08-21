---
description: radio 컨트롤에 bind 를 지정할 때 사용하는 속성이다.     
---

#   bind                       

## DESCRIPTION

bind 를 radio 에 연결시키면 사용하면 집적 radio 에 인스턴스를 맵핑하는 것이 아니라 
radio 에 맵핑된 bind 의 ref 에 설정된 XPath 의 경로에 있는 인스턴스가 
radio 에 맵핑된 인스턴스의 역할을 한다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="payway" bind="pay" overflow="visible" appearance="full" style="left:550px; top:470px; width:70px; height:40px; border-style:none; ">
```
{% endcode %}