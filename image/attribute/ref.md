---
description: img 컨트롤에 맵핑될 인스턴스의 XPath 경로를 설정하는 속성이다.
---

# ref

## DESCRIPTION

디자이너상에서 인스턴스를 드래그하여 맵핑하면 ref 속성에 설정할 수 있고, 직접 caption 컨트롤의 ref 속성에 맵핑할 인스턴스의 경로를 입력하여 설정할 수 있다.

img 컨트롤에 설정하는 ref 속성의 값은 img 의 경로를 나타내는 경로값이 설정되어 있어야 해당 이미지가 나타난다.

맵핑된 인스턴스에 속성으로 type = "xsd:base64Binary" 로 설정된 경우 해당 데이터를 decoding 하여 이미지로 변환해서 보여준다.


{% hint style="info" %}
src 속성으로 image 가 설정되어 있고, ref 속성으로 image 의 경로가 설정되어 있을 경우에는 ref 속성으로 설정된 경로의 image 를 화면에 보여준다. 
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
img id="img1" ref="/root/Basic/img1" style="left:40px; top:215px; width:165px; height:155px; background-stretch:stretch; "/> 
```
{% endcode %}



