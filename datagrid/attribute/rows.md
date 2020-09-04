---
description: Light Grid 를 사용할 때 초기에 보여줄 행의 갯수를 설정하는 속성이다.
---

# rows

## DESCRIPTION

datagrid 를 Light Grid 로 사용하기 위해서는 datagrid 의 datatype attribute 를 delimeter 로 설정해야 한다. Light Grid 는 기본적으로 nodeset 을 가지고 모든 col 들도 인스턴스와 맵핑을 하는것이 원칙이지만 실제로 인스턴스를 사용하지는 않는다. 

그러므로 초기 로딩시 datagrid 와 맵핑된 인스턴스가 존재하더라도 데이터 행이 나타나지 않는다. 

Light Grid 를 초기에 로딩할 때 빈 데이터 행들을 보여주도록 설정하는 것이 rows 속성이다.

rows 로 설정한 행들은 defaultrows 로 설정한 행들과 다르게 선택이 되고 동작을 하는 실제 행들이다.

Light Grid 의 자세한 사용법은 TrustForm5.0 가이드 &gt; 컨트롤 &gt; grid 컨트롤 &gt; Light grid 사용하기 참고. 

## VALUES

* **seq / reverseseq / select / update**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/grid" caption="caption1^caption2^caption3"
 colsep="^" datatype="delimeter" mergecellsfixedrows="bycolrec" rows="5" 
 rowsep="|" style="left:35px; top:40px; width:350px; height:150px; ">
```
{% endcode %}

