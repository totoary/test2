---
description: 그리드의 행이 Multi Update 상태 중 update 상태일 때 rowheader 에 표시할 이미지를 설정하는 속성이다.
---

# updateflagimage

## DESCRIPTION

update 상태는 그리드의 행이 사용자에 의해 수정된 상태이다. 이 속성은 rowheader attribute 가 update 일 때만 동작을 한다.

Multi Update 의 자세한 사용법은 TrustForm4.0 가이드 &gt; 컨트롤 &gt; grid 컨트롤 &gt; Multi Update 를 참고.

이 속성을 설정하지 않으면 디폴트 update 플래그 이미지가 설정된다. \(초록색 마크\)

## VALUES

Picture Files \(bmp.dib.emf.gif.ico.jpg.wmf\)\|_.bmp;_.dib;_.emf;_.gif;_.ico;_.jpg;_.wmf\|BMP \(_.bmp\)\|_.bmp\|DIB \(_.dib\)\|_.dib\|EMF \(_.emf\)\|_.emf\|GIF \(_.gif\)\|_.gif\|ICO \(_.ico\)\|_.ico\|JPG \(_.jpg\)\|_.jpg\|WMF \(_.wmf\)\|_.wmf\|All Files \(_._\)\|_.\*\|\|\)

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/employeeSample/gridData1/employee" 
backcolorfrozen="#ffff99" caption="Name^Age^Gender^Address" colsep="^" 
colwidth="76, 68, 79, 225" frozencols="1" mergecellsfixedrows="bycolrec" 
rowheader="seq" rowsep="|" tooltip="label" style="left:35px; top:295px; 
width:320px; height:185px; ">
```
{% endcode %}

