---
description: 아이템을 배치하기 위한 열의 개수를 설정하는 속성이다.
---

# cols

## DESCRIPTION

Integer 형의 숫자를 써주면 아이템들이 설정된 cols 만큼의 열에 배치가 된다.

cols 를 설정하고 direction attribute 를 accrossdown 또는 downacross 로 설정하면 가로로 먼저 배치할지 세로로 먼저 배치 할지 정할 수 있다

이 속성을 설정하지 않으면 1 로 설정한것처럼 동작한다.   

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="listbox2" ref="/root/selected2" overflow="visible" appearance="compact" cols="2" 
style="left:245px; top:270px; width:180px; height:140px; border-style:none; ">
```
{% endcode %}
