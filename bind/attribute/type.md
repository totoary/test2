---
description: ref 에 지정된 노드의 type 을 지정해주는 속성이다.
---

# type

## DESCRIPTION

인스턴스의 데이터 타입이 반드시 특정 타입이어야 하는 경우에 사용한다. 노드의 타입이 type 과 같으면\(valid\) 연결된 컨트롤에 xforms-valid 이벤트를, 수행 결과가 invalid 이면 xforms-invalid 이벤트를 발생 시킨다. xforms-valid 와 xforms-invalid 이벤트는 최초 로딩시점, model.revalidate\(\) 를 수행할 때, 사용자가 입력값을 바꿀때 또는 model.refresh\(\) 를 수행할 때 발생한다.

## VALUES

xsd:anyURI / xsd:base64Binary / xsd:boolean / xsd:byte / xsd:date / xsd:dateTime xsd:decimal

xsd:double / xsd:float / xsd:gDay / xsd:gMonth / xsd:gMonthDay xsd:gYear / xsd:gYearMonth

xsd:hexBinary / xsd:int / xsd:integer / xsd:long xsd:negativeInteger / xsd:nonNegativeInteger

xsd:nonPositiveInteger / xsd:normalizedString xsd:positiveInteger / xsd:short / xsd:string

xsd:time xsd:unsignedByte / xsd:unsignedInt / xsd:unsignedLong / xsd:unsignedShort

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<bind id="ageBind" ref="/root/information/age" type="xsd:positiveInteger"/>
```
{% endcode %}

