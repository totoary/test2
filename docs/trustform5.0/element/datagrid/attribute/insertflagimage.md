---
description: 그리드의 행이 Multi Update 상태 중 insert 상태일 때 rowheader 에 표시할 이미지를 설정하는 속성이다.
---

# insertflagimage

## DESCRIPTION

insert 상태는 그리드에서 새로 추가된 행에 설정되는 상태이다. 이 속성은 rowheader 가 update 일 때만 동작을 한다.

Multi Update 의 자세한 사용법은 TrustForm5.0 가이드 &gt; 컨트롤 &gt; grid 컨트롤 &gt; Multi Update 를 참고.

이 속성을 설정하지 않으면 디폴트 insert 플래그 이미지가 설정된다. \(파란색 마크\)

## VALUES

* **Picture Files \(bmp.dib.emf.gif.ico.jpg.wmf\)\|.bmp;.dib;.emf;.gif;.ico;.jpg;.wmf\|BMP \(.bmp\)\|.bmp\|DIB \(.dib\)\|.dib\|EMF \(.emf\)\|.emf\|GIF \(.gif\)\|.gif\|ICO \(.ico\)\|.ico\|JPG \(.jpg\)\|.jpg\|WMF \(.wmf\)\|.wmf\|All Files \(.\)\|.\*\|\|**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid4" nodeset="/root/g" caption="caption1^caption2^caption3" 
colsep="^" insertflagimage="insert.jpg" mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:430px; top:290px; width:350px; height:150px; ">
```
{% endcode %}

