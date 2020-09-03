---
description: 아이템을 배치하기 위한 행의 개수를 설정하는 속성이다.
---

# rows

## DESCRIPTION

cols 속성이 아이템의 배열을 계산하는 주가 되므로 cols 를 Integer로 설정해 놓으면 rows를 설정하더라도 아이템 배열에는 영향을 주지 않는다.  
rows를 이용하여 아이템 배열의 기준을 설정하려면 반드시 cols가 '\*'로 설정 되어 있어야한다.

rows 를 설정하고 cols 를 '_' 로 설정한 후 direction attribute 를 accrossdown 또는 downacross 로 설정하면 가로로 먼저 배치할지 세로로 먼저 배치할지를 정할 수 있다. 이 속성을 설정하지 않으면 기본으로 '_' 이 설정된다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="checkbox" overflow="visible" appearance="full" cols="*" rows="2" 
style="left:70px; top:365px; width:110px; height:65px; border-style:none; ">
```
{% endcode %}

