---
description: 그리드의 Multi Update 정보에서 행 구분자를 지정하는 속성이다.
---

# rowsep

## DESCRIPTION

Multi Update 기능은 그리드 내의 정보를 사용자가 추가,수정,삭제 등을 하였을 때 그 내용을 관리하는 기능이다. \(TrustForm5.0 가이드 &gt; 컨트롤 &gt; grid 컨트롤 &gt; Multi Update 참고\)

rowsep 속성은 이 Multi Update 기능 중 getUpdateData\(\) 와 같은 함수를 사용하였을 때 반환되는 문자열에서 행 구분자를 설정하는 속성이다.

이 속성을 설정하지 않으면 기본으로 " \| " 가 구분자로 지정된다.

## VALUES

* **seq / reverseseq / select / update**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/grid" caption="caption1^caption2^caption3"
 colsep="^" datatype="delimeter" mergecellsfixedrows="bycolrec" rows="5" 
 rowsep="~" style="left:35px; top:40px; width:350px; height:150px; ">
```
{% endcode %}

