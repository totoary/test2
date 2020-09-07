---
description: 컨트롤의 포커스 이동 순서인 navigation index 를 설정하는 속성이다.
---

# navindex

## DESCRIPTION

navindex 가 -1 이면 해당 컨트롤은 navigation index 에 영향을 받지 않는다. tab key 를 이용한 포커스 이동에서 제외된다. 마우스를 이용한 포커스 이동은 가능 만약 여러개의 컨트롤들의 navindex 를 똑같이 설정 해 두면 그 컨트롤들 간의 순서는 예측 할 수 없다.

navindex 가 설정 되어 있는 컨트롤들과 navindex 속성을 갖지 않는 컨트롤들이 함께 존재 할 경우, navindex 가 설정되어 있는 컨트롤들이 먼저 포커스를 갖고, 그 후에 navindex 속성이 없는 컨트롤들에 포커스가 가게 된다.

TF 에서는 모든 컨트롤은 navindex 를 가진다. Output 같은 컨트롤은 포커스를 갖지 않는 컨트롤이기 때문에 디폴트로 navindex 가 -1 로 셋팅 되어 있다.

스크립트에서 동적으로 navindex 를 변경하기 위해서는 navindex property 를 사용해야 한다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<bool id="bool1" navindex="1" ref="/root/a" style="left:345px; top:60px; width:100px; height:20px; "/>
```
{% endcode %}

