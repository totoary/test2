---
description: datagrid 가 여러 장에 걸쳐 print 될 때 모든 페이지 마다 caption 영역을 print 할 지 여부를 정하는 속성이다.
---

# caption-layout

## DESCRIPTION

* flow : datagrid 가 여러 장에 걸쳐 print 될 때 caption 영역을 모든 페이지 마다 print 한다.
* static : 모든 페이지 마다 print 하지 않는다.

  \(속성을 설정하지 않으면 기본값은 “static " 이다\)

## **VALUES**

* **flow / static\(default\)**

## EXAMPLE

{% code title="\[Static \]" %}
```bash
<datagrid id="datagrid4" nodeset="/root/scrollSample/gridData/bankTransfer" 
scroll="auto" caption="Bank^Date^Receiver^Amount" colsep="^" 
colwidth="100, 100, 100, 100" mergecellsfixedrows="bycolrec" rowsep="|" 
caption-layout="flow" style="left:6px; top:8px; width:325px; height:190px; ">
```
{% endcode %}

