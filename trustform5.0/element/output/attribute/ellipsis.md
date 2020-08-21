---
description: 컨트롤에 말줄임 기능을 설정하는 속성이다.
---

# ellipsis

## DESCRIPTION

텍스트 데이터의 길이가 컨트롤의 너비 값보다 클 경우 이 속성을 true 로 설정하면 컨트롤의 너비만큼 텍스트 데이터가 보여지고, "..."으로 말줄임 기호를 보여준다. ellipsis 속성을 설정하지 않으면 기본적으로 false 와 같이 동작한다.

{% hint style="info" %}
Attribute 의 ellipsis 는 최초 로딩 시 말줄임 기능을 설정하는 속성이므로 ellipsis 를 스크립트에서 동적으로 제어하기 위해서는 ellipsis property 를 사용해야 한다.
{% endhint %}

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<output id="titleout" ellipsis="true" style="left:160px; top:230px; width:100px; 
height:20px; font-weight:bold; color:#808080; vertical-align:middle; ">
```
{% endcode %}

