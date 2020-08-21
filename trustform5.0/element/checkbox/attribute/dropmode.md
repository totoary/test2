---
description: 다른 컨트롤에서 드래그 한 값을 현재 컨트롤에 드롭할 수 있도록 해주는 속성이다
---

# dropmode

## DESCRIPTION

dropmode 를 true 로 설정하면 사용자가 마우스로 다른 컨트롤에서 드래그 한 후 checkbox 컨트롤에 드롭 동작을 할 수 있도록 설정만 해주는 것이다. 실제로 컨트롤의 값을 dragData 로 바꾸거나, 그 외 다른 동작을 수행 하고 싶은 경우에는, ondrop 이벤트에서 event.dropData 에 있는 데이터를 넣어주거나 수행하고싶은 동작을 수행하면 된다. 이 속성은 설정하지 않으면 기본으로 false 가 설정된다,

* drag & drop 은 application view 에서는 동작하지 않고 IE 에서만 동작한다.  

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="checkbox3" ref="/root/zz" dropmode="true" appearance="full" 
style="left:395px; top:455px; width:100px; height:55px; border-style:none; ">
```
{% endcode %}

