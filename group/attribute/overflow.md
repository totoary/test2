---
description: group 컨트롤에서 자식 컨트롤들이 차지하는 영역에 대한 표현방법을 설정하는 속성이다.
---

# overflow

## DESCRIPTION

_visible : 모든 컨트롤들이 화면에 표시될 수 있도록 group 의 영역을 확장하거나 축소한다._ hidden : 자식 컨트롤들이 group 의 영역을 벗어나면 영역을 벗어난 컨트롤들은 화면에 보이지 않도록 한다. \*scroll : 자식 컨트롤들이 group 의 영역을 벗어나면 스크롤바를 보여준다.

이 속성을 설정하지 않으면 기본으로 scroll 로 설정한 것과 같이 동작한다.

## VALUES

visible / hidden / scroll\(default\)

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<group id="group1" overflow="visible" style="left:130px; top:245px; width:200px; height:150px; "/>
```
{% endcode %}

