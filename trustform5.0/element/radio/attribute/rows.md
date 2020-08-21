---
description: 아이템을 배치하기 위한 행의 개수를 설정하는 속성이다.    
---

#   rows                       

## DESCRIPTION
cols 속성이 아이템의 배열을 계산하는 주가 되므로 cols 를 Integer 로 설정해 놓으면 rows 를 설정하더라도 아이템 배열에는 영향을 주지 않는다.  
rows 를 이용하여 아이템 배열의 기준을 설정하려면 반드시 cols 가 '*'로 설정되어 있어야한다. 

rows 를 설정하고 cols 를 '*' 로 설정한 후 direction attribute 를 accrossdown 또는 downacross 로 설정하면 가로로 먼저 배치할지 세로로 먼저 배치할지를 정할 수 있다.

이 속성을 설정하지 않으면 기본으로 '*' 이 설정된다   

## EXAMPLE

{% code title="\[Static\]" %}
```markup
select1 id="radio3" ref="/root/selected3" appearance="full" cols="*" 
direction="downacross" rows="2" overflow="visible" 
style="left:40px; top:435px; width:130px; height:23px; border-style:none; ">  
```
{% endcode %}