---
description: src 로 지정된 싱글 노드를 삭제한다.
---

# copyNode

## DESCRIPTION

파라미터로 주어진 하나의 노드를 삭제하는 함수로서, 그리드와 같이 여러 파일을 삭제할 경우 for 문을 사용하면 여러 파일의 삭제가 가능하다.

파라미터로 주어진 노드 하위에 노드들이 존재할 경우에는 지정된 노드와 하위의 모든 노드들도 삭제가 된다.

파라미터로 설정한 노드는 XPath 식 또는 노드 객체로 선언할 수 있다.

* 파라미터로 설정한 노드가 인스턴스에 존재하지 않을 경우에는 아무런 동작을 하지 않는다. 

## SYNTAX

```
model.copyNode(String destRef, String srcRef) 
```

## EXAMPLE

{% code title="\[JavaScript\]" %}
```bash
<script id="script2" type="javascript" ev:event="DOMActivate">

      <![CDATA[

            model.copyNode( "/root/res", "/root/grid" );

            model.copyNode( root.res, root.grid );

      ]]>

</script>

```
{% endcode %}






