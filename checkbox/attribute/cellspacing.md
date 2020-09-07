---
description: 아이템과 아이템 사이의 가로 방향 간격을 지정하는 속성이다.
---

# cellspacing

## DESCRIPTION

아이템과 아이템 사이의 가로 방향 간격을 지정하는 속성이다. cellspacing 과 itemwidth 는 비슷한 속성인데 차이는 다음과 같다.

cellspacing 은 item의 넓이 길이는 제외한 아이템과 아이템 사이의 간격만을 지정하는 속성이고, itemwidth 는 하나의 아이템이 차지하는 전체 넓이 공간을 지정하는 속성이다.

이 속성은 설정하지 않으면 기본으로 0 이 설정이 된다.

## EXAMPLE

{% code title="Static" %}
```markup
<select id="checkbox" overflow="visible" appearance="full" cellspacing="50" cols="3" 
direction="acrossdown" style="left:395px; top:455px; width:100px; height:85px; border-style:none; ">
```
{% endcode %}

