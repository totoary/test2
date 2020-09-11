---
description: 바인드에 연결되어 있는 노드 리스트를 얻는다.
---

# nodeset

### DESCRIPTION

바인드 속성 중 ref 에 설정 되어 있는 노드의 리스트를 얻어오는 것으로, nodeList 객체를 반환한다.

### SYNTAX

\[ nodeList = \] bind.nodeset

### GET VALUES

nodeList : ref 에 설정 되어 있는 노드의 리스트

### EXAMPLE

{% code title="\[JavaScript\]" %}
```markup
<script type="javascript" ev:event="DOMActivate">
    <![CDATA[                                                     
        var nodelist = bind.nodeset;
        var node;
        while( node = nodelist.nextNode() )
            {
                if (node!=null)            
                    output1.value += node.xml + "\n";
            }
    ]]>
</script>
```
{% endcode %}

