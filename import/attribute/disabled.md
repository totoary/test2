---
description: import 컨트롤의 disabled(비활성화) 상태를 설정하는 속성이다.
---

# disabled

## DESCRIPTION

* Attribute 의 disabled 은 단지 컨트롤의 초기 상태를 의미한다. 그러므로 스크립트에서 enabled/disabled 를 조작 하려면 disabled property 를 사용 해야 한다.

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<import id="import1" disabled="true" src="disabled_sample.xrw" 
style="left:95px; top:85px; width:200px; height:150px; "/>
```
{% endcode %}

