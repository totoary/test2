---
description: 바인드된 컨트롤의 disabled 상태를 제어하는 속성
---

# readonly

## DESCRIPTION

상황에 따라 특정 컨트롤의 disabled 상태를 제어 할 때 유용하게 쓰이며, 속성에 쓴 XPath 수식이 true\(\) 가 되는 경우 맵핑되어 있는 컨트롤이 disabled 상태가 된다.

bind 창을 통해서 생성시 참고.
* Bind ID : bind 의 ID.
* ref : disabled 상태로 만들 인스턴스의 경로
* 속성 : disabled 상태가 되어야 하는 XPath{

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<bind id="bind1" ref="/root/next" readonly="/root/agreement/agree != 'T'"/>
```
{% endcode %}

