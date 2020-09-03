---
description: group 컨트롤을 popup 윈도우로 화면에 표시할 지 여부를 설정하는 속성이다.
---

# popup

## DESCRIPTION

popup 을 true 로 설정하면 group 컨트롤을 popup 윈도우로 화면에 보여주고, 이 때 화면에 보여주는 popup 의 위치는 윈도우의 screen 좌표이다.
윈도우의 screen 좌표로 화면에 보여주기 때문에 popup 설정할 경우 group 의 좌표를 윈도우의 screen 좌표에 맞게 설정한 후 보여줘야 한다.

popup 속성을 설정하지 않으면 기본으로 false 로 설정이 된다.

{% hint style="info" %} popup 을 true 로 설정하여 group 이 popup 형태로 나타날 때 showeffect 속성을 설정하여 popup 이 나타나는 방식을 지정할 수 있다. 
(group > attribute > showeffect 참고)   
{% endhint %}

## VALUES

true / false(default)

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<group id="addGroup" popup="true" showeffect="blend 300" style="left:30px; top:225px; width:290px; height:145px; /">
```
{% endcode %}