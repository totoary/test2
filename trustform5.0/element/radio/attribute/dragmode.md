---
description: 컨트롤에서 드래그를 할 수 있도록 해주는 속성이다.
---

#   dragmode                       

## DESCRIPTION

dragmode 를 true 로 설정하면 사용자가 마우스로 radio 컨트롤에서 드래그 동작을 할 수 있도록 설정만 해준다.
드래그 시 특정값을 dragData 에 넣거나, 그 외 다른 동작을 수행 하고 싶은 경우에는 ondragstart 이벤트에서 
event.dropData 에 데이터를 넣어주거나 수행하고싶은 동작을수행하면 된다.

combo, treeview, radio, checkbox, listbox 는 label과 value 값을 동시에 가지기 때문에 
반드시 ondragstart 이벤트에서 드래그시 동작을 정의해 주어야한다.

* drag & drop 은 application view 에서는 동작하지 않고 IE 에서만 동작한다. 

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="shirtColor" ref="/root/shirtColor" dragmode="true" overflow="visible" 
appearance="full" style="left:125px; top:315px; width:100px; height:70px; 
border-style:none; "> 
```
{% endcode %}
