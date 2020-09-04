# alwaysdrawbutton

### description:자식이 없는 마지막 아이템에 펼치기 닫기 마크\(+,-\)를 보여줄 지, 안 보여줄 지를 설정하는 속성이다.

## alwaysdrawbutton

### DESCRIPTION

alwaysdrawbutton 속성을 true 로 설정하면 해당 아이템의 자식 유무와 상관없이 \(+,-\) 마크를 그려서 화면에 보여주고, false 로 설정하면 자식이 없는 아이템에 \(+,-\) 마크를 그리지 않는다.

이 속성을 true 로 설정하여 자식이 없는 아이템에도 \(+,-\)마크를 화면에 보여주는데, 특정한 아이템의 \(+,-\)마크를 보여주지 않도록 설정할 수 있다. \(+,-\)마크를 보여주지 않을 아이템에 @lastdepth="true" 를 설정하면 해당 아이템에는 \(+,-\)마크를 그리지 않는다. 만약 자식이 있는 아이템 노드에 @lastdepth="ture" 를 설정하여도 반영되지 않는다.

이 속성을 설정하지 않으면 기본으로 false 로 설정한 것과 같이 동작한다

### VALUES

true / false\(default\)

### EXAMPLE

{% code title="\[Static\]" %}
```markup
<treeview id="treeview1" alwaysdrawbutton="true" style="left:20px; top:45px; width:250px; height:210px; ">
```
{% endcode %}

