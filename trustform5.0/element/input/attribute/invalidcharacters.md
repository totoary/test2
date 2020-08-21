---
description: input컨트롤에 입력하지 못하게 할 문자를 설정합니다.
---

#   invalidcharacters                        

## DESCRIPTION
[string] = 컨트롤ID.attribute("invalidcharacters") = [string]
[string]에 지정된 문자는 입력이 불가능합니다.
컨트롤ID.attribute("invalidcharacters") = "abcd";
-> abcd를 제외한 다른 문자만 입력이 가능하게 됩니다.

한글인 경우는 imemode  속성을 사용하여 입력을 제어 할 수 있습니다.(한글 입력 가부만 결정가능합니다.)  

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="input1" invalidcharacters="abcd" style="left:55px; top:60px; width:100px; height:20px; "/>  
```
{% endcode %}

{% code title="\[Dynamic\]" %}
```markup
input1.attribute("invalidcharacters") = "abcd";   
```
{% endcode %}

