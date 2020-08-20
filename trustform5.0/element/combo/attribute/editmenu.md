---
description: >-
  editmenu 속성은 combo 컨트롤이 edit 상태일때 마우스 오른쪽 버튼을 클릭할 경우 edit 메뉴가 보일지, 사용자 정의 메뉴가
  보일지 설정하는 속성.
---

# editmenu

## DESCRIPTION

dropmode 를 true 로 설정하면 사용자가 마우스로 다른 컨트롤에서 드래그 한 후 combo 컨트롤에 드롭 동작을 할 수 있도록 한다.

true : 기존과 동일하게 edit 상태에서 오른쪽 버튼을 누를경우 SetPopupMenu 와 상관없이 edit 관련 메뉴가 출력된다. false : edit 상태에서 오른쪽 버튼 SetPopupMenu 가 설정되어 있으면 해당 사용자 메뉴가 출력되고, 설정되어 있지 않으면 edit 관련 메뉴가 나타난다.

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="combo2" ref="/root/input_combo" appearance="minimal" 
editmode="input" editmenu="false" style="left:260px; top:403px; 
width:200px; height:20px; ">
```
{% endcode %}

