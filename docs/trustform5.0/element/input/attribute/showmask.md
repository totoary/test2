---
description: format 이 설정되어 있을 때 입력모드가 되면 포맷 형식을 알 수 있도록 mask 를 표현해주는 속성이다.    
---

#   showmask                       

## DESCRIPTION

format 이 설정되어 있고, input 컨트롤에 값이 없어야 되고, 입력모드 (edit mode) 상태이어야 한다.
이 속성이 true 로 설정되어 있고, format 이 999-999 로 설정되어 있으면 사용자가 이 포맷형식을 알 수 있도록 " ___-___ " 와 같이 표현을 해준다.

이 속성을 설정하지 않으면 기본으로 false 로 설정한 것처럼 mask 문자를 표시하지 않는다
  
## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="frame" ref="/root/frame" format="yyyy/mm/dd" showmask="true" style="left:374px; top:49px; width:100px; height:20px; "/>  
```
{% endcode %}

