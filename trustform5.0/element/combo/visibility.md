---
description: combo 컨트롤을 화면에 표시할 지를 설정하는 속성이다.
---

# visibility

## DESCRIPTION

* visible : combo 컨트롤이 보인다.
* hidden : combo 컨트롤이 보이지 않는다.

이 속성을 설정하지 않으면 기본으로 visible 로 동작한다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 visibility 를 동적으로 제어하기 위해서는 visible property 를 사용한다
{% endhint %}

## VALUES

visible / hidden 

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="nationCombo" ref="/root/country" visibility="visible" appearance="minimal" style="left:50px; top:345px; width:125px; height:25px; ">  
```
{% endcode %}
