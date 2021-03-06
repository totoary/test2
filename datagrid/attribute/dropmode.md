---
description: 컨트롤에서 드롭을 할 수 있도록 설정하는 속성이다.
---

# dropmode

##  DESCRIPTION

컨트롤에서 드롭을 할 수 있도록 설정하는 속성이다. dropmode 를 true 로 설정하면 사용자가 마우스로 다른 컨트롤에서 drag 한 것을 datagrid 컨트롤에 드롭 동작을 할 수 있도록 설정만 해주는 것이다. 실제로 dropData 의 값을 datagrid 컨트롤에 넣거나, 그 외 다른 동작을 수행 하고 싶은 경우에는, ondrop 이벤트에서 event.dropData 의 데이터를 datagrid 에 넣거나 수행하고싶은 동작을 수행하면 된다.

\(주의\) drag & drop 은 application view 에서는 동작하지 않고 IE 에서만 동작한다.

* Drag & Drop 의 자세한 사용법은  TrustForm5.0 &gt; Drag&Drop 사용하기  참고.

이 속성을 설정하지 않으면 기본으로 false 로 설정된다.

## VALUES

* **true / false\(default\)**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/g" dropmode="true" caption="caption1^
caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:35px; top:35px; width:350px; height:150px; ">
```
{% endcode %}



