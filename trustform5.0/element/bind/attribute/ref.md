---
description: bind 에 맵핑되어 있는 ref 속성      
---

#   ref                       

## DESCRIPTION

컨트롤에 bind 가 맵핑되어 있으면 컨트롤은 ref 가 없어도 bind 에 설정되어 있는 이 ref 가 맵핑되어 있는것과 동일하게 동작한다.

* 컨트롤에 ref 속성이 설정되어 있을 때 bind 를 설정하면 bind 에 설정된 ref 가 우선적으로 적용된다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<bind id="bind1" ref="/root/ok" />  
```
{% endcode %}
