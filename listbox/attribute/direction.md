---
description: 아이템을 배치할 방향을 설정하는 속성이다.
---

# direction

## DESCRIPTION

아이템을 배치할 방향을 설정하는 속성이다. cols attribute 를 반드시 설정 해야 동작한다. cols 에 설정한 열의 갯수로 아이템의 갯수를 나누어서 각 행, 열에 배치될 아이템의 갯수를 먼저 정하게 된다.

direction 을 acrossdown 으로 설정하면 세로로 먼저 배치하고 downacross 로 설정하면 가로로 먼저 배치한다. 이 속성을 설정되지 않으면 기본으로 acrossdown 으로 동작하게 된다.

* 이 속성을 설정되지 않으면 기본으로 acrossdown 으로 동작하게 된다.   

## VALUES

acrossdown / downacross

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="listbox2" ref="/root/selectedData2" overflow="visible" appearance="compact" cols="2" 
direction="downacross" itemwidth="100" style="left:385px; top:260px; width:165px; height:95px; 
background-color:#ffff99; border-width:1px; border-style:solid; ">
```
{% endcode %}

