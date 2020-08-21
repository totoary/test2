---
description: radio 컨트롤에 맵핑될 인스턴스의 XPath 경로를 지정하는 속성이다.   
---

#   ref                       

## DESCRIPTION

radio 의 item 중 선택된 item 의 value 값이 ref 에 지정된 인스턴스에 저장된다.
{% hint style="info" %}동적으로 ref를 변경할 경우 refresh를 호출하여야 인스턴스가 radio에 반영된다.{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="way" ref="/root/payway" overflow="visible" appearance="full" 
style="left:85px; top:270px; width:100px; height:20px; border-style:none; "> 
```
{% endcode %}