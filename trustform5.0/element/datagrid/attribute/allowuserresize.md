# allowuserresize

description: 그리드의 fixed cell 의 구분선을 더블클릭 해서 데이터의 길이만큼 행 또는 열의 넓이를 자동으로 변경할수 있도록 설정하는 속성이다.

### \(열의 넓이를 조절하려면 caption 구간의 구분선을 더블클릭하고, 행의 높이를 조절하려면 좌측 fixedcell 구간의 구분선을 더블클릭하면 된다.\)

## autosizemouse

### DESCRIPTION

그리드 셀의 데이터가 셀이 표현할 수 있는 길이보다 길 경우 행 또는 열의 넓이가 자동으로 늘어나고 셀의 데이터가 짧을때는 줄어든다. 셀에 내용이 없는 경우에는 행이나 열의 넓이가 변하지 않는다. 단, 이 기능은 사용자가 행이나 열의 넓이를 조정할 수 있어야 하기 때문에 allowuserresize 속성이 true 로 설정되어 있을 때에만 동작한다.

이 속성은 설정하지 않으면 기본으로 false 로 설정이 된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 autosizemouse 를 동적으로 제어하기 위해서는 autoSizeMouse property 를 사용한다. 

### **VALUES**

* **true / false\(default\)\**

### EXAMPLE

{% code title="\[Static \]" %}
```bash
<datagrid id="datagrid1" nodeset="/root/g" allowuserresize="true" 
caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" 
rowsep="|" autosizemouse="true" style="left:305px; top:165px; width:350px;
 height:150px; ">
```
{% endcode %}

