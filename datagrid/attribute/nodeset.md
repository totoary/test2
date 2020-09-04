---
description: 그리드와 맵핑된 인스턴스 노드셋을 설정하는 속성이다.
---

# nodeset

## DESCRIPTION

디자이너의 인스턴스 창에서 인스턴스 노드셋을 마우스로 드래그하여 datagrid 컨트롤에 드롭하면 자동으로 맵핑이 되고 nodeset attribute 에 자동으로 XPath 식이 입력된다. 

그리드에 인스턴스 노드셋을 맵핑하면, 그리드 하위에 있는 각 col 들에는 그리드에 맵핑된 인스턴스 하위의 노드셋들이 자동으로 ref 로 설정된다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 nodeset 를 동적으로 제어하기 위해서는 nodeset property 를 사용한다.
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/martSample/gridData/itemList/item" 
caption="caption1^caption2^caption3^caption4" colsep="^" colwidth="100, 100, 100, 
100" mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:45px; top:70px; width:520px; height:195px; ">
```
{% endcode %}

