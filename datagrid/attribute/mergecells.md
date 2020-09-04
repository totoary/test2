---
description: 그리드의 행이 Multi Update 상태 중 insert 상태일 때 rowheader 에 표시할 이미지를 설정하는 속성이다.
---

# mergecells

## DESCRIPTION

그리드에서 병합은 label 값이 아닌 value\(인스턴스에 저장되는 값\) 을 기준으로 한다.

* bycol : 상하만 머지를 한다.
* byrow : 좌우만 머지를 한다.
* bycolrec : 상하좌우를 모두 머지한다.
* byrowrec : 상하좌우를 모두 머지한다. 좌우 머지를 우선 적용한 후 상하 머지를 한다.
* byrestriccol : 상하만 머지를 한다. 첫번째 열부터 순서대로 머지를 한다. 머지를 할 영역은 이전 열의 머지 결과에 의해 결정된다.
* byrestricrow : 좌우만 머지를 한다. 첫번째 행부터 순서대로 머지를 한다. 머지를 할 영역은 이전 행의 머지 결과에 의해 결정된다.

그리드의 셀 병합의 자세한 내용은 TrustForm5.0 가이드 &gt; 컨트롤 &gt; grid 컨트롤 &gt; cell 병합하기 참고

이 속성을 설정하지 않으면 데이터 셀들이 머지되지 않는다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 mergecells 를 동적으로 제어하기 위해서는 mergeCells property 를 사용한다.
{% endhint %}

## VALUES

* **never / byrow / bycol / byrowrec / bycolrec / byrestriccol / byrestricrow**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/g" caption="caption1^caption2^caption3^
caption4" colsep="^" colwidth="100, 100, 100, 100" mergecells="bycol" 
mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:30px; top:35px; width:430px; height:225px; ">
```
{% endcode %}

