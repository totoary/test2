---
description: bind 가 수행할 스크립트를 설정하는 속성
---

# script

## DESCRIPTION

이 속성 설정된 스크립트는 최초 로딩시점, model.recalculate\(\) 가 되는 시점, 사용자가 값을 바꾸거나 model.refresh\(\) 가 되는 시점에 스크립트가 수행된다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<bind id="ageBind" ref="/root/information/age" type="xsd:positiveInteger"/>
```
{% endcode %}

