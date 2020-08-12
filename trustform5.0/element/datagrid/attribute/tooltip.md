---
description: 그리드의 툴팁을 설정하는 속성이다.
---

#   tooltip                       

## DESCRIPTION

이 속성을 true 로 설정하면 그리드 셀 위에 마우스가 올라가 있을때 셀의 내용이 그대로 툴팁으로 보여진다.
col 의 type 이 combo 일 경우, tooltip 의 내용은 화면에 보이는 label 값이 아닌 인스턴스에 저장되는 value 값이 보이게 된다.
만약 이 속성을 .label 로 설정하면 col 의 type 이 combo 인 셀의 tooltip 내용이 화면에 보이는 label 값으로 보이게 되고, 다른 셀들은 true 로 설정되었을 때 보여지는 대로 툴팁을 보여준다.
툴팁으로 보여지는 내용을 셀의 내용이 아닌 다른 내용으로 변경하고 싶을 경우에는 tooltipText property 를 사용하면 된다.

datagrid 컨트롤의 hint attribute 와 함께 설정이 되어 있을 경우 tooltip 이 우선 적용이 된다. (적용 우선순위 : tooltip > hint)
즉, tooltip 이 true 이고 hint 속성에 값이 설정이 되어있는 경우, 데이터 셀에 마우스를 올려놓으면 tooltip 이 적용이 되고, 데이터 구간이 아닌 곳에 마우스를 올려 놓으면 hint 속성에 설정한 값이 나타난다.

이 속성을 설정하지 않으면 false 로 설정한 것과 같이 동작한다.

* 툴팁이 화면에 표시될 때 표시될 툴팁 내용이 화면(모니터)을 벗어날 경우 모니터의 해상도 좌표를 얻어와서 툴팁의 위치, 크기를 비교한 후 화면에 알맞게 보여주도록 되어 있다.

* label 값으로 설정할 때, coltype 이 combo 인 경우에는 label 이 존재하기 때문에 label 값으로 툴팁을 보여주지만, checkbox 나 radio 와 같이 label 이 없는 셀렉트 타입의 colType 은 value 값으로 툴팁을 보여준다.                              
   
## VALUES

label / true / false(default)   

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/employeeSample/gridData1/employee" backcolorfrozen="#ffff99" caption="Name^Age^Gender^Address" colsep="^" colwidth="76, 68, 79, 225" frozencols="1" mergecellsfixedrows="bycolrec" rowheader="seq" rowsep="|" tooltip="label" style="left:35px; top:295px; width:320px; height:185px; "> 
```
{% endcode %}



