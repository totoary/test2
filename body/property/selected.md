---
description: body 컨트롤의 선택 상태를 설정할 수 있는 property 이다. 
---

# selected  

### DESCRIPTION
사용자가 실제로 body 컨트롤을 선택할 수는 없지만, 디자인 시점에 select 에 대한 스타일을 주고 선택상태를 true 로 해주면 select 의 스타일이 적용된다.
TrustForm 에서는 기본적으로 모든 컨트롤들이 selected 상태가 존재한다. 

### SYNTAX
[ Boolean = ] body.selected [ = Boolean ] 

### PUT VALUES
Boolean : 설정할 선택 상태(실제 선택은 되지 않음)
     - true
     - false
	 
### GET VALUES
Boolean : 설정된 선택 상태(실제 선택은 되지 않음)
     - true
     - false
	 
### EXAMPLE
{% code title="\[JavaScript\]" %}
```markup
<xhtml:body select.background-color="#999999">
<script id="script1" type="javascript" ev:event="DOMActivate">
    <![CDATA[
        body.selected = true;
    ]]>
</script>
```
{% endcode %}

