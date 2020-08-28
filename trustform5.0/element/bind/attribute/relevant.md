---
description: 바인드 된 컨트롤의 visibility 를 제어하는 속성이다. 
---

#   relevant                        

## DESCRIPTION

속성에 쓰여진 XPath의 계산값이 true() 일때 맵핑되어 있는 컨트롤이 보이게 되고 false() 일때는 숨겨진다.

{% hint style="info" %}* bind창을 통해서 생성시 참고.
  - Bind ID : bind의 ID.
  - ref : 수식을 통해 나온 결과 값에 따라 visibility 를 제어 할 인스턴스의 경로
  - 속성 : XPath 수식{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<bind id="bind1" ref="/root/ok" relevant="/root/name='' or /root/sex='' or /root/age='' or /root/email=''"/>  
```
{% endcode %}
