---
description: 그리드 컨트롤에 배경 이미지를 설정하는 속성이다.
---

# wallpaper

## DESCRIPTION

invert로 설정하면 텍스트의 색상이 반전되고, none 으로 설정하면 셀이 선택되어도 텍스트의 색상이 변하지 않는다.

단, 배경 이미지가 있는 셀은 selectimagestyle 이 "none" 으로 설정되어 있으면 selectfontcolorstyle 가 무시되어 "none" 으로 설정한 것과 같이 동작하고, selectimagestyle 이 "invert" \(default\) 로 설정되어 있을 때에만 selectfontcolorstyle 이 적용된다. 또한, focuscolor 가 설정되어 있을 때에도 selectfontcolorstyle 은 무시되고 "none" 으로 설정한 것과 같이 동작한다. -&gt; 적용 우선순위 : selectimagestyle, focuscolor &gt; selectfontcolorstyle

이 속성을 설정하지 않으면 기본으로 invert 로 설정이 되어서 선택된 셀의 텍스트의 색상이 반전된다.

* attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 selectfontcolorstyle 을 동적으로 제어하기 위해서는 selectFontColorStyle property 를 사용한다.                         

## VALUES

Picture Files \(bmp.dib.emf.gif.ico.jpg.wmf\)\|_.bmp;_.dib;_.emf;_.gif;_.ico;_.jpg;_.wmf\|BMP \(_.bmp\)\|_.bmp\|DIB \(_.dib\)\|_.dib\|EMF \(_.emf\)\|_.emf\|GIF \(_.gif\)\|_.gif\|ICO \(_.ico\)\|_.ico\|JPG \(_.jpg\)\|_.jpg\|WMF \(_.wmf\)\|_.wmf\|All Files \(_._\)\|_.\*\|\|

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/grid" caption="caption1^caption2^caption3"
 colsep="^" mergecellsfixedrows="bycolrec" rowsep="|" selectfontcolorstyle="none" 
 style="left:150px; top:50px; width:350px; height:150px; ">
```
{% endcode %}

