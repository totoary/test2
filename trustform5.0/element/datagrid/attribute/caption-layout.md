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
<datagrid id="datagrid1" nodeset="/root/grid" 
caption="Category1^Category1^Category2^Category2|Item1^Item2^Item3^Item4" 
colsep="^" colwidth="100, 100, 100, 100" mergecellsfixedrows="bycolrec" rowsep="|"
 style="left:40px; top:220px; width:480px; height:260px; "> 
```
{% endcode %}

