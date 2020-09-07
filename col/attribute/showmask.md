---
description: format 이 설정되어 있을 때 입력모드가 되면 mask 를 표현해주는 속성 
---

# showmask 

## DESCRIPTION

format 이 설정되어 있고 셀에 값이 없어야 되고 입력모드(edit mode) 상태여야 한다.
이 속성이 true 로 설정되어 있고 format 이 999-999 로 설정되어 있으면 사용자가 이 포맷형식을 알수 있도록 ___-___ 와 같이 표현을 해준다.

이 속성을 설정하지 않으면 기본으로 false 로 설정한 것 처럼 mask 문자를 표시하지 않는다.   

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col ref="idNumber" type="input" format="999-999" showmask="true"/> 
```
{% endcode %}
