---
description: datagrid 컨트롤을 화면에 표시할 지를 설정하는 속성이다.
---

#   visibility                       

## DESCRIPTION

- visible : datagrid 컨트롤이 보인다.
- hidden : datagrid 컨트롤이 보이지 않는다.

이 속성을 설정하지 않으면 기본으로 visible 로 동작한다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 visibility 를 동적으로 제어하기 위해서는 visible property 를 사용한다                                
   
## VALUES

visible(default) / hidden   

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid2" nodeset="/root/scrollSample/gridData/grid" visibility="hidden" caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" rowsep="|" style="left:45px; top:215px; width:350px; height:150px; "> 
```
{% endcode %}

{% code title="\[Dynamic\]" %}
```markup
<script type="javascript" ev:event="DOMActivate">

      <![CDATA[

            datagrid1.visible = false;

      ]]>

</script> 
```
{% endcode %}



