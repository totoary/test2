---
description: 아이템과 아이템 사이의 가로 방향 간격을 지정하는 속성이다.
---

# cellspacing

## DESCRIPTION

cellspacing 과 itemwidth 는 비슷한 속성인데 차이는 다음과 같다.

_cellspacing : item의 넓이 길이를 제외한 아이템과 아이템 사이의 간격만을 지정하는 속성_ itemwidth :하나의 아이템이 차지하는 전체 넓이 공간을 지정하는 속성이다.

이 속성은 아이템간의 가로방향 간격을 지정하는 것이기 때문에 cols attribute 를 설정해야 효과가 나타난다

## VALUES

cellspacing / itemwidth

## EXAMPLE

{% code title="Static" %}
```markup
<select1 id="radio2" ref="/root/radio2" appearance="full" cellspacing="30" cols="2" 
style="left:305px; top:280px; width:255px; height:90px; background-color:#ccffcc; 
border-style:solid; ">
```
{% endcode %}

