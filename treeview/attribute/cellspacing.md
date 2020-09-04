# cellspacing

### description:트리 아이템 상하간의 간격을 지정하는 속성이다.

## cellspacing

### DESCRIPTION

음수 값을 설정하여 간격을 좁히는 것이 가능하다.  
cellspacing 과 itemwidth 는 비슷한 속성인데 차이는 다음과 같다.

_cellspacing : 아이템간 상하간의 간격을 지정하는 속성_ itemheight : 아이템 자체의 높이를 설정하는 속성

### VALUES

cellspacing / itemheight

### EXAMPLE

{% code title="\[Static\]" %}
```markup
<treeview id="stuTree1" ref="/root/selected1" cellspacing="20" expanddepth="1" style="left:50px; top:255px; width:220px; height:155px; background-color:#ffd9fc; ">
```
{% endcode %}

