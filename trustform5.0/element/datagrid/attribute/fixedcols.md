---
description: 스크롤이 되지 않는 fixed col(고정된 열)의 갯수를 설정하는 속성이다.
---

# fixedcols 

## DESCRIPTION

스크롤이 되지 않는 fixed col(고정된 열)의 갯수를 설정하는 속성이다.
Fixed Col 은 캡션과 같이 스크롤이 되지 않고 선택도 되지 않는 열이다.
이 속성에 설정된 숫자는 rowheader 의 갯수를 포함한다. 그러므로 rowheader 속성을 설정하고 fixedcols 를 1로 설정하면 rowheader 만 설정했을 경우와 똑같이 동작한다.

이 속성을 설정하지 않으면 기본으로 fixed col 의 갯수는 0 으로 설정된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 fixedcols 를 동적으로 제어하기 위해서는 fixedCols property 를 사용한다.   

## VALUES



## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid3" nodeset="/root/g" caption="caption1^caption2^caption3" colsep="^" extendlastcol="noscroll" fixedcols="1" mergecellsfixedrows="bycolrec" rowsep="|" style="left:430px; top:260px; width:350px; height:145px; "> 
```
{% endcode %}



