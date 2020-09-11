---
description: 
---

# attribute 

### DESCRIPTION
컨트롤의 부모 객체를 반환한다.  부모객체란 TrustFrom xrw 문서에서의 parent Element 를 말한다.  
TrustForm 의 객체 구조상 body 는 최상의 Element 인 html 바로 아래에 존재하므로 body 의 parent 는 항상 html 이 되겠다.
따라서 body 의 parent 의 elementName 을 확인해보면  xfoms:html 이 나온다.
 
### SYNTAX
[ Element = ] body.parent 

### GET VALUES
Element : 부모의 element
 
### EXAMPLE

{% code title="\[JavaScript\]" %}
```markup
<script id="script1" type="javascript" ev:event="DOMActivate">
    <![CDATA[
        alert( body.parent.elementName );
    ]]>
</script>
```
{% endcode %}

