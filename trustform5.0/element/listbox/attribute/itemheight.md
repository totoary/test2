---
description: 아이템의 높이를 설정하는 속성이다.
---

# itemheight

## DESCRIPTION

itemheight 와 vcellspacing 은 비슷한 속성인데 차이는 다음과 같다. 

itemheight 는 아이템 자체의 높이를 지정하는 속성이고, vcellspacing 은 item 의 높이를 제외한 아이템과 아이템 사이의 세로 간격만을 지정하는 속성이다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="listboxItemHeight" ref="/root/select2" overflow="visible" 
appearance="compact" itemheight="20" style="left:290px; top:260px; width:90px; 
height:185px; background-color:#ffcc99; border-style:solid; "> 
```
{% endcode %}


