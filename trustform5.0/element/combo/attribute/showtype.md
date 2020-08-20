---
description: '콤보 리스트에 value 값만, 혹은 label 값만, 혹은 value/lable값을 동시에 보이도록 설정한다.'
---

# showtype

## DESCRIPTION

* value : Value 값만 보임
* label : label 값만 보임
* all : value 값과 label 값을 동시에 보임

이 속성을 설정하지 않으면 기본으로 showtype="all" 과 같이 동작한다.

## VALUES

value / label / all

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="itemCombo" ref="/root/selectedItem" showtype="value"  
appearance="minimal" showvalue="true" style="left:110px; top:260px; 
width:225px; height:20px">
```
{% endcode %}

