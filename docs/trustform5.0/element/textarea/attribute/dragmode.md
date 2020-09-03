---
description: textarea 컨트롤에서 드래그를 할 수 있도록 해주는 속성이다.
---

# dragmode

## DESCRIPTION

dragmode 를 true 로 설정하면 사용자가 마우스로 textarea 컨트롤에서 드래그를 하면 event.dropData 에 드래그된 데이터가 저장된다. 드래그 동작을 수행할 때 dropmode 속성이 true 로 설정되어 있는 컨트롤에 드래그한 값을 드롭할 수 있다.

드래그 시 이외에 다른 동작을 원하는 경우 ondragstart 이벤트에서 스크립트를 설정하면 된다.

이 속성은 설정하지 않으면 기본으로 false가 설정된다.

* drag & drop 은 application view 에서는 동작하지 않고 IE 에서만 동작한다. 

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<textarea id="textarea1" ref="/root/from" dragmode="true" style="left:30px; top:25px; width:220px; height:205px; "/>
```
{% endcode %}

