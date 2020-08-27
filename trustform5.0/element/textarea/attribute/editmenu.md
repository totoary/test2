---
description: 
  editmenu 속성은 textarea 컨트롤이 edit 상태일때 마우스 오른쪽 버튼을 클릭할 경우 edit 메뉴가 보일지, 사용자 정의 메뉴가
  보일지 설정하는 속성.
---

# editmenu

## DESCRIPTION

* true : 기존과 동일하게 edit 상태에서 오른쪽 버튼을 누를경우 SetPopupMenu 와 상관없이 edit 관련 메뉴가 출력된다.
* false : edit 상태에서 오른쪽 버튼 SetPopupMenu 가 설정되어 있으면 해당 사용자 메뉴가 출력되고, 설정되어 있지 않으면 edit 관련 메뉴가 나타난다.  

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<textarea id="textarea3" ref="/root/textarea" editmenu="false" style="left:260px; top:252px; width:200px; height:79px; "/> 
```
{% endcode %}

