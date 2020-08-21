---
description: checkbox 컨트롤에 맵핑될 인스턴스의 XPath 경로를 지정하는 속성이다.
---

# ref

## ref

### DESCRIPTION

checkbox 에 맵핑되어 있는 인스턴스에는 checkbox 의 item 중 체크된 것들의 value 값이 구분자\(sep\)로 구분되어 저장된다. 구분자는 sep attribute 로 지정할 수 있고, default 는 띄어쓰기 구분자\(space\) 이다.

{% hint style="info" %}
동적으로 ref를 변경할 경우 refresh를 호출하여야 인스턴스가 checkbox에 반영된다.
{% endhint %}

### EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="studentList" ref="/root/attendanceA" overflow="hidden" appearance="full" 
cellspacing="75" cols="4" style="left:55px; top:315px;width:400px; height:170px; border-style:none;">
```
{% endcode %}

## ref

