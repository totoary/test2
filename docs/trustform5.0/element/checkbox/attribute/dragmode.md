---
description: 컨트롤에서 드래그를 할 수 있도록 해주는 속성이다.
---

# dragmode

## DESCRIPTION

dragmode true 로 설정하면 사용자가 마우스로 checkbox 컨트롤에서 드래그 동작을 할 수 있도록 설정만 해주는 것이다. 실제로 컨트롤의 값을 dragData 에 넣거나, 그 외 다른 동작을 수행 하고 싶은 경우에는, ondragstart 이벤트에서 event.dropData 에 데이터를 넣어주거나 수행하고싶은 동작을 수행하면 된다. 이 속성은 설정하지 않으면 기본으로 false가 설정된다.

* drag & drop 은 application view 에서는 동작하지 않고 IE 에서만 동작한다. 

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="options" ref="/root/checkedOptions" dragmode="true" overflow="visible" 
appearance="full" style="left:100px; top:315px; width:135px; eight:140px; border-style:none; ">
```
{% endcode %}

