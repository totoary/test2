---
description: textarea 컨트롤의 영역을 넘는 내용에 대한 표현 방법을 설정하는 속성이다.    
---

#   overflow                       

## DESCRIPTION

*visible : 내용이 textarea 의 영역을 벗어나면 모든 내용이 textarea 에 표시될 수 있도록 textarea 의 영역을 확장한다.
*hidden : 내용이 textarea 의 영역을 벗어나면 영역을 벗어난 내용은 화면에 보이지 않도록 한다.
*scroll :  내용이 textarea 의 영역을 벗어나면 스크롤바를 보여준다.

이 속성을 설정하지 않으면 기본으로 scroll 로 설정한 것과 같이 동작한다.   

## VALUES

visible / hidden / scroll  

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<textarea id="homeTextarea" ref="/root/addressSample/introduce" overflow="visible" 
style="left:55px; top:335px; width:330px; height:140px; ">  
```
{% endcode %}