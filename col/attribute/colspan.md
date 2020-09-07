---
description: multilinegrid 에서 셀의 가로 병합 상태를 설정하는 속성이다.
---

# colspan

## DESCRIPTION

이 속성은 사용자가 attribute 창에서 직접 설정하는 것이 아니라 multilinegrid 에서 가로로 인접한 셀들을 ctrl 키와 마우스를 사용하여 선택한 후 마우스 오른쪽 클릭 메뉴에서 병합을 누르면 자동으로 설정이 되는 것이다. 2개의 셀을 병합하면 colspan 이 2가 되고 3개의 셀을 병합하면 colspan 이 3이된다.

세로 병합의 상태는 rowspan attribute 에 설정이 된다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col colspan="2" ref="a"/>
```
{% endcode %}

