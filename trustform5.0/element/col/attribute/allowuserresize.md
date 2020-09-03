---
description:사용자가 마우스로 열의 크기를 조절할 수 있게 할지를 설정한다.
---

# allowuserresize 

## DESCRIPTION
이 속성이 true 로 설정되어 있을 때 마우스를 fixed row(캡션부분) 의 가장자리로 가져가면 마우스 포인터가 크기를 조절하는 포인터로 바뀌고 그 위치에서 드래그를 하여 열의 크기를 조절 할 수 있다.

사용자가 마우스로 열의 크기를 조절하면 크기가 변경되기 전에 onbeforeuserresize 이벤트가 발생하고 크기가 조절 된 후에 onafteruserresize 이벤트가 발생한다.

이 속성은 설정하지 않으면 기본으로 true 로 설정한 것 처럼 동작한다.   
{% hint style="info" %}
{% endhint %}
## VALUES
true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col ref="col1" type="input" format="hh:nn:ss"/> 
```
{% endcode %}
