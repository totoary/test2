---
description: listbox 가 자식 아이템들이 차지하는 영역에 대한 표현 방법 설정하는 속성이다.
---

# overflow

## DESCRIPTION

_visible : 모든 자식 아이템이 화면에 표시될 수 있도록 listbox 영역을 확장하거나 축소한다._ hidden : 아이템들이 listbox의 영역을 벗어나면 해당 영역은 화면에 보이지 않도록 한다. \*scroll : 아이템들이 listbox의 영역을 벗어나면 스크롤바를 표시한다.

이 속성을 설정하지 않으면 기본으로 visible 이 설정된다.

## VALUES

visible / hidden / scroll

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="menu" ref="/root/yourMenu" overflow="scroll" appearance="compact" cols="4" 
itemwidth="140" style="left:85px; top:285px; width:445px; height:145px; border-style:none; ">
```
{% endcode %}

