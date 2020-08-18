---
description: 컨트롤에서 드래그를 할 수 있도록 해주는 속성이다.
---

#   dragmode                      

## DESCRIPTION

dragmode true 로 설정하면 사용자가 마우스로 combo 컨트롤에서 드래그 동작을 할 수 있도록 설정만 해준다.

드래그시 특정값을 dragData 에 넣거나, 그 외 다른 동작을 수행 하고 싶은 경우에는,
ondragstart 이벤트에서 event.dropData 에 데이터를 넣어주거나 수행하고싶은 동작을 수행하면 된다.

combo, treeview, radio, checkbox, listbox 는 label과 value 값을 동시에 가지기 때문에 반드시 
ondragstart 이벤트에서 드래그시 동작을 정의해 주어야한다.

* drag & drop 은 application view 에서는 동작하지 않고 IE 에서만 동작한다.  
                      
## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="shirtColor" ref="/root/shirtColor" dragmode="true" appearance="minimal" style="left:110px; top:320px; width:105px; height:25px; text-align:center; background-color:transparent; "> 
```
{% endcode %}
