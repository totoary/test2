---
description: '잘못된 또는 깨진 데이터를 복사하여 입력 가능한 컨트롤에 붙여넣기를 하려고 할 때, 잘못된 데이터를 붙여넣을 지 유무를 설정하는 속성이다.'
---

# pastemode

## DESCRIPTION

pastemode 속성을 default 로 설정하면 기존에 동작하던 것처럼 잘못된 데이터를 포함한 모든 데이터를 붙여넣을 수 있도록 설정 되고, validchars 로 설정하면 잘못된 데이터 즉, 클립보드에 깨진문자가 복사된 값을 붙여넣기하려고 할 때, 붙여넣기 동작을 수행하지 않는다.

이 속성을 설정하지 않으면 기본으로 default 가 설정된다.\(모든 값 붙여넣기 가능\)

## VALUES

default / validchars

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="input" ref="/root/select/" appearance="minimal" editmode="input" pastemode="validchars" style="left:225px; top:280px; width:100px; height:20px; ">  
```
{% endcode %}



