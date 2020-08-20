---
description: 화면에 보이는 아이템 리스트의 길이를 결정하는 속성이다.
---

# itemcount

## DESCRIPTION

attribute itemcount를 설정하면 콤보를 펼쳤을때 combo list 에 나타나는 아이템의 갯수가 설정한 숫자대로 제한된다.

이 속성을 설정하지 않으면 기본으로 아이템 갯수는 30으로 설정된다.

* 이 속성의 최대값은 30 이다.  

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="combo1" ref="/root/univ" appearance="minimal" itemcount="2" 
style="left:130px; top:280px; width:240px; height:20px; ">
```
{% endcode %}

