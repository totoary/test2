<<<<<<< HEAD
---
description: listbox 컨트롤에 맵핑될 인스턴스의 XPath 경로를 지정하는 속성이다. 
---

=======
>>>>>>> 39a9e6e02e8ed3a645ed43cf175046a74b66407c
# ref

### &lt;&lt;&lt;&lt;&lt;&lt;&lt; HEAD

### description: combo 컨트롤에 맵핑될 인스턴스의 XPath 경로를 지정하는 속성이다.

## ref

### DESCRIPTION

listbox 에 맵핑되어 있는 인스턴스에는 listbox 의 item 중 선택된 것들의 value 값이 구분자(sep) 로 구분되어 저장된다.
구분자는 sep attribute 로 지정할 수 있고, default 는 띄어쓰기 구분자(space) 이다.

* 동적으로 ref를 변경할 경우 refresh를 호출하여야 인스턴스가 listbox에 반영된다.

<<<<<<< HEAD
=======
### EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="way" ref="/root/payway" appearance="minimal" 
style="left:75px; top:270px; width:110px; height:20px; ">
```
{% endcode %}

### =======

### description: combo 컨트롤에 맵핑될 인스턴스의 XPath 경로를 지정하는 속성이다.

## ref

### DESCRIPTION

combo 의 item 중 선택된 item 의 value 값이 ref 에 지정된 인스턴스에 저장된다.

* 동적으로 ref를 변경할 경우 refresh를 호출하여야 인스턴스가 combo 에 반영된다. 

### EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="way" ref="/root/payway" appearance="minimal" 
style="left:75px; top:270px; width:110px; height:20px; ">
```
{% endcode %}

> > > > > > > eaecbff44ad16a728baa64cf76485a2e44cd3f57

>>>>>>> 39a9e6e02e8ed3a645ed43cf175046a74b66407c
