---
description: 그리드 열을 화면에 표시할 지를 설정하는 속성이다.
---

# visibility

## DESCRIPTION

_visible : 열이 보인다._ hidden : 열이 보이지 않는다.

Attribute 의 visibility 는 최초 로딩 시 열을 보여줄지 설정하는 속성이므로 visibility 를 스크립트에서 동적으로 제어하기 위해서는 datagrid 의 colHidden property 를 사용한다.

## VALUES

visible / hidden

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col ref="idx" visibility="hidden"/>
```
{% endcode %}

