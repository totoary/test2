---
description: listbox 에 맵핑된 인스턴스의 구분자를 설정 하는 속성이다.     
---

#   sep                       

## DESCRIPTION

listbox의 item 이 선택 되었을때 맵핑된 인스턴스에 해당 item의 value 값이 저장된다.  
listbox는 다중선택이 가능하기 때문에 인스턴스에 여러개의 item value 값이 들어갈 수 있다.  

이때 인스턴스에 저장된 item 의 value 값들을 구분할 구분자를 지정한다.
이 속성을 설정하지 않으면 기본으로 " "(space)가 설정된다. 
  
## VALUES

| / ^ / ▦

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="sampleListbox" ref="/root/selectedData" overflow="scroll" 
appearance="compact" sep="|" style="left:60px; top:260px; width:150px; 
height:140px; border-style:solid; "> 
```
{% endcode %}
