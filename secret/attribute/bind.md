---
description: secret 컨트롤에 bind 를 지정할 때 사용하는 속성이다.
---

# bind

## DESCRIPTION

bind 창에서 bind 를 설정한 다음 bind 를 사용할 secret 컨트롤에 bind ID 를 설정하여 사용한다.
bind 를 사용하면 calculate, constraint 등 편리한 기능을 사용할 수 있다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<secret id="secret1" bind="bind1" ref="/root/Basic" imemode="disabled" 
style="left:500px; top:190px; width:100px; height:20px; "/>
```
{% endcode %}

