---
description: textarea 컨트롤에 맵핑될 인스턴스의 XPath 경로를 지정하는 속성이다.
---

# ref

## DESCRIPTION

textarea 컨트롤에 입력된 내용은 맵핑된 인스턴스에 저장된다. ref 는 직접 코드상에서 설정해도 무방하지만, 인스턴스 창에서 인스턴스를 생성한 후, 인스턴스를 마우스로 드래그하여 맵핑해주면, textarea 컨트롤의 ref 속성이 자동으로 설정이 된다.

{% hint style="info" %}
동적으로 ref 를 변경할 경우 refresh 를 호출하여야 인스턴스가 textarea 에 반영된다.
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<textarea id="homeTextarea" ref="/root/addressSample/introduce" style="left:55px; top:335px; width:330px; height:140px; ">
```
{% endcode %}



