---
description: 텍스트 데이터의 길이에 따라 caption  컨트롤의 크기를 자동으로 조절하는 속성이다.
---

# autoresize

## DESCRIPTION

이 속성을 true 로 설정할 경우 텍스트의 길이가 길면 자동으로 caption 이 넓어지고 짧으면 좁아지게 된다. output 에 텍스트 데이터가 없는 경우에는 caption 이 보이지 않는다.

autoresize 속성을 설정하지 않으면 기본값은 false 이다.

## VALUES

true / false\(default\)

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<caption id="caption5" autoresize="true" style="left:45px; top:260px; width:100px; height:20px; ">
```
{% endcode %}

