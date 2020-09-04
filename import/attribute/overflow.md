---
description: import 컨트롤에서 자식 컨트롤들이 차지하는 영역에 대한 표현 방법을 설정하는 속성이다.
---

# overflow

## DESCRIPTION

* visible : 모든 컨트롤들이 화면에 표시될 수 있도록 import 의 영역을 확장하거나 축소한다.
* hidden : 자식 컨트롤들이 import 의 영역을 벗어나면 영역을 벗어난 컨트롤들은 화면에 보이지 않도록 한다. 

  \*scroll : 자식 컨트롤들이 import 의 영역을 벗어나면 스크롤바를 보여준다.

이 속성을 설정하지 않으면 기본으로 scroll 로 설정한 것과 같이 동작한다.

## VALUES

visible / hidden / scroll

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<import id="import1" overflow="scroll" scroll="both" src="sample.xrw" 
style="left:145px; top:135px; width:200px; height:150px; "/>
```
{% endcode %}

