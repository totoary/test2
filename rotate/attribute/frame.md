---
description: null
---

# frame

## DESCRIPTION

1/1000초 를 기본단위로 애니메이션 효과를 반복할 시간을 설정하는 속성이다. frame="100" 일 경우, 0.1초 마다 화면을 렌더링한다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<animation id="ani1">
    <scale id="scale1" during="1000" frame="30" target="input1" widthTo="200" heightTo="100"/>
</animation>
```
{% endcode %}

