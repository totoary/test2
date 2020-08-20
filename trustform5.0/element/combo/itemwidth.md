---
description: 아이템의 높이를 설정하는 속성이다.
---

# itemwidth

## DESCRIPTION

itemwidth 와 cellspacing 은 비슷한 속성인데 차이는 다음과 같다. itemwidth 는 아이템 자체의 넓이를 지정하는 속성이고, cellspacing 은 item 의 넓이를 제외한 아이템과 아이템 사이의 가로 간격만을 지정하는 속성이다.  
이 속성을 설정하지 않으면 기본으로 itemwidth 는 combo 의 width 와 동일하게 된다.

{% hint style="info" %}
itemwidth 가 combo 의 width 보다 크게 설정되어 있다면 item 의 넓이는 itemwidth 에 설정한 값으로 고정된다. 하지만 설정한 itemwidth 가 combo의 width 보다 작게 되면 설정한 itemwidth 는 무시되며 이때 item 의 넓이는 기본으로 combo 의 width 로 설정된며 아이템의 label 의 길이에따라 item 의 넓이가 늘어난다\(combo 자체의 width 보다는 작게 설정되지 않는다\)
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="combo1" appearance="minimal" style="left:110px; top:285px; width:100px; height:21px; ">
```
{% endcode %}

