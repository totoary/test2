---
description: 그리드 최상위의 fixedrow 영역에 들어갈 caption 텍스트를 설정하는 속성이다.
---

# caption

## DESCRIPTION

각 열의 제목에 해당하는 텍스트를 열 구분자\(^\) 로 구분하여 설정할 수 있다. datagrid 의 캡션부분이 다중 행일 경우, 여러 행의 캡션 텍스트를 행 구분자\(\|\) 로 구분하여 설정해 줄 수 있다.

datagrid 의 caption 속성은 디자이너에서 datagrid 를 그린 후 caption 부분을 더블클릭하여 텍스트를        수정하면 자동으로 설정이 된다. 이웃하는 셀의 캡션이 같은 텍스트의 이름을 갖을 경우 자동으로 merge\(병합\)이 되는데 이는 datagrid 의 mergecellsfixedrows 속성이 default 로 bycolrec 으로 설정이 되기 때문이다.

* caption property 를 이용하여 "\^"를 캡션에 설정할 때에는 "\^" 와 같이 "\"을 두개 사용해야 한다. 이유는 스크립트의 스트링에서 "a\n" 등의 방식으로 사용할수 있기때문에 일반적으로 문자열내의  는 \ 로 표기하기 때문이다. 또한, attribute는 그자체가 이스케이프 문자를 사용할 수 없는 문자열이기때문에  를 바로 문자로 인식하기 때문이다.
* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 caption 을 동적으로 제어하기 위해서는 caption property 를 사용한다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/grid" 
caption="Category1^Category1^Category2^Category2|Item1^Item2^Item3^Item4" 
colsep="^" colwidth="100, 100, 100, 100" mergecellsfixedrows="bycolrec" rowsep="|"
 style="left:40px; top:220px; width:480px; height:260px; "> 
```
{% endcode %}

