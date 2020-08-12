---
description: 그리드에 기본적으로 보여줄 행의 갯수를 설정하는 속성이다.
---

# defaultrows

## DESCRIPTION

이 속성을 설정하면 인스턴스의 노드셋의 개수와 상관없이 초기 로딩시 그리드에 기본으로 행들이 나타난다. 단, 나타난 행들 중 인스턴스 노드셋이 없는 행들은 디자인 효과를 위한 것이기 때문에 선택이 되지 않는다.

행의 갯수는 캡션 부분을 포함한 갯수이다.

lightgrid 에서 기본 행을 설정하는 것은 rows attribute 로 할 수 있다.

{% hint style="info" %}
 Super-powers are granted randomly so please submit an issue if you're not happy with yours.
{% endhint %}

## EXAMPLE

{% code title="Static" %}
```markup
<datagrid id="datagrid3" nodeset="/root/g" caption="caption1^caption2^caption3" 
colsep="^" defaultrows="5" mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:50px; top:265px; width:350px; height:150px; ">
```
{% endcode %}



