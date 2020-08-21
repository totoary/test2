<<<<<<< HEAD
---
description: listbox 컨트롤에 bind 를 지정할 때 사용하는 속성이다.
---

=======
>>>>>>> 39a9e6e02e8ed3a645ed43cf175046a74b66407c
# bind

### &lt;&lt;&lt;&lt;&lt;&lt;&lt; HEAD

### description: combo 컨트롤에 bind 를 지정할 때 사용하는 속성이다.

## bind

### DESCRIPTION

combo 컨트롤에 bind 를 지정할 때 사용하는 속성이다. bind 를 사용하면 calculate, constraint 등 편리한 기능을 사용할 수 있다.

<<<<<<< HEAD
bind 를 사용하면 calculate, constraint 등 편리한 기능을 사용할 수 있다.  
bind를 listbox에 연결시키면 사용하면 집적 listbox에 인스턴스를 맵핑하는 것이 아니라 listbox 에 맵핑된
bind 의 ref 에 설정된 XPath의 경로에 있는 인스턴스가 listbox에 맵핑된 인스턴스의 역할을 한다.  
=======
bind 를 checkbox 에 연결시키면 사용하면 집적 combo 에 인스턴스를 맵핑하는 것이 아니라 combo 에 맵핑된 bind 의 ref 에 설정된 XPath 경로에 있는 인스턴스가 combo 에 맵핑된 인스턴스의 역할을 한다.
>>>>>>> 39a9e6e02e8ed3a645ed43cf175046a74b66407c


### EXAMPLE

{% code title="\[Static\]" %}
```markup
<select id="kind" bind="readable" overflow="scroll" appearance="compact" 
style="left:140px; top:350px; width:105px; height:115px; font-weight:bold; 
text-align:center; background-color:#ffff99; border-color:#ccffff; border-width:5px; border-style:dashed; ">
```
{% endcode %}
<<<<<<< HEAD
=======

### =======

### description: combo 컨트롤에 bind 를 지정할 때 사용하는 속성이다.

## bind

### DESCRIPTION

combo 컨트롤에 bind 를 지정할 때 사용하는 속성이다. bind 를 사용하면 calculate, constraint 등 편리한 기능을 사용할 수 있다.

bind 를 checkbox 에 연결시키면 사용하면 집적 combo 에 인스턴스를 맵핑하는 것이 아니라 combo 에 맵핑된 bind 의 ref 에 설정된 XPath 경로에 있는 인스턴스가 combo 에 맵핑된 인스턴스의 역할을 한다.

이 속성은 설정하지 않으면 bind는 설정이 되지 않는다.

### EXAMPLE

{% code title="\[Static\]" %}
```markup
<select1 id="payway" bind="select" appearance="minimal" 
style="left:270px; top:465px; width:65px; height:20px; ">
```
{% endcode %}

> > > > > > > eaecbff44ad16a728baa64cf76485a2e44cd3f57

>>>>>>> 39a9e6e02e8ed3a645ed43cf175046a74b66407c
