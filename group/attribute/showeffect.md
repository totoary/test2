---
description: group 컨트롤이 popup 인 경우 화면에 보여지는 방법을 설정하는 속성이다.
---

# showeffect

## DESCRIPTION

group 컨트롤에서 popup 속성을 true 로 설정한 경우 showeffect 속성을 설정하여 popup 형태의 group 컨트롤을 화면에 보여질 때 보여지는 방법을 설정할 수 있다.

* blend 300 : popup 형태의 group 이 보여지는 위치에서 부드럽게 나타난다.
* slidepositive 500 : popup 형태의 group 이 위에서 보여지는 위치로 내려오며 나타난다. 
* slidenegative 500 : popup 형태의 group 이 아래에서 보여지는 위치로 올라가며 나타난다.

{% hint style="info" %}
popup 속성을 설정하지 않으면 showeffect 속성을 설정해도 동작하지 않는다.
{% endhint %}

## VALUES

blend 300 / slidepositive 500 / slidenegative 500

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<group id="addGroup" popup="true" showeffect="blend 300" style="left:30px; top:225px; width:290px; height:145px; /">
```
{% endcode %}

