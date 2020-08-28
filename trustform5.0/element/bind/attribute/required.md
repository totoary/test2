---
description: 필수항목을 체크하는 속성     
---

#    required                        

## DESCRIPTION
required 속성에 설정된 XPath 수식이 true() 가 되는 경우 ref 의 인스턴스와 맵핑 되어있는 컨트롤이 required 속성을 가지게 된다. 
required 속성이 true() 가 된 컨트롤은 사용자가 입력 값을 바꾸거나 model.refresh() 되는 시점마다 xforms-required 이벤트를 발생 시키고 속성이 false() 라면 
xforms-optional 이벤트를 발생시킨다. 

submission 을 수행하기 직전에만 필수 항목을 체크하기 위해서 xforms-required-error 를 사용하면 유용하다. 
주의 할 점은 필수 항목을 체크하는 인스턴스가 submission 의 ref 에 해당하지 않는다면 xforms-required-error 이벤트는 발생하지 않는다.
 
{% hint style="info" %} 입력 컨트롤(예를 들면 input)의 required attribute 를 true 로 설정하여 필수항목을 만들 수도 있지만, bind 의 required 는 다른 항목에 의존하여 필수항목으로 만들 때 사용된다.  
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<bind id="bind1" ref="/root/other" required="/root/nationality = 'other'"/>  
```
{% endcode %}



