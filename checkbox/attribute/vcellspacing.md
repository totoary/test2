---
description: 아이템과 아이템 사이의 세로 방향 간격을 지정하는 속성이다.
---

# vcellspacing

## DESCRIPTION

vcellspacing 과 itemheight 는 비슷한 속성인데 차이는 다음과 같다. vcellspacing 은 item의 높이 길이는 제외한 아이템과 아이템 사이의 간격만을 지정하는 속성이고, itemheight 는 하나의 아이템이 차지하는 전체 넓이 공간을 지정하는 속성이다.

이 속성은 설정하지 않으면 기본으로 0 이 설정이 된다

## VALUES

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="checkbox2" ref="/root/checkbox2" overflow="visible" appearance="full" 
cols="2" vcellspacing="10" style="left:375px; top:290px; width:95px; height:230px; 
background-color:#99ccff; border-style:none; ">
```
{% endcode %}

