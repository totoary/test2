---
description: 그리드에 말줄임 기능을 사용하도록 설정하는 속성이다.
---

# ellipsis

## DESCRIPTION

이 속성이 true 로 설정 되어 있으면 셀 내용의 길이가 셀의 넓이보다 길때 말줄임 표시\( ... \)로 잘린 부분을 표현한다.

datagrid 컨트롤의 autoresize 기능이 true 로 설정이 되어 있는 경우에는 이 속성이 무시된다.         autoresize 기능은 셀 내용의 길이가 셀의 넓이보다 길 경우 셀의 크기를 자동으로 넓혀주는 기능이기 때문이다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 ellipsis 를 동적으로 제어하기 위해서는 ellipsis property 를 사용한다.
{% endhint %}

## VALUES

* **true / false\(default\)**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid2" nodeset="/root/g" caption="caption1^caption2^caption3" 
colsep="^" ellipsis="true" mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:50px; top:260px; width:350px; height:150px; "> 
```
{% endcode %}



