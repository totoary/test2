---
description: 아이템의 높이를 설정하는 속성이다.
---

# itemwidth

## DESCRIPTION

itemwidth 와 cellspacing 은 비슷한 속성인데 차이는 다음과 같다. 
itemwidth 는 아이템 자체의 넓이를 지정하는 속성이고, cellspacing 은 item 의 넓이를 제외한 아이템과 아이템 사이의 가로 간격만을 지정하는 속성이다.  

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="listboxWeight" ref="/root/select2" overflow="visible" appearance="compact" cols="2" 
itemwidth="60" style="left:255px; top:320px; width:110px; height:95px; border-style:solid; "> 
```
{% endcode %}
