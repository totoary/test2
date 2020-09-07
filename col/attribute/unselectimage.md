---
description: radio 가 선택 해제 되었을 때의 이미지를 설정하는 속성
---

# unselectimage

## DESCRIPTION

type attribute 가 "radio" 이고 선택 되지 않은 상태일 때 보여질 이미지를 설정하는 속성이다. 이미지의 경로는 절대경로 또는 상대경로를 설정한다.

type attribute 가 "radio" 가 아닐 때에는 설정해도 동작하지 않는다. 선택이 되어 있는 상태일 때 보여질 이미지는 selectimage attribute 로 설정할 수 있다.

## VALUES

Picture Files \(bmp.dib.emf.gif.ico.jpg.wmf\)\|_.bmp;_.dib;_.emf;_.gif;_.ico;_.jpg;_.wmf\|BMP \(_.bmp\)\|_.bmp\|DIB \(_.dib\)\|_.dib\|EMF \(_.emf\)\|_.emf\|GIF \(_.gif\)\|_.gif\|ICO \(_.ico\)\|_.ico\|JPG \(_.jpg\)\|_.jpg\|WMF \(_.wmf\)\|_.wmf\|All Files \(_._\)\|_.\*\|\|

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col unselectimage="image.gif" ref="col1" type="radio"/>
```
{% endcode %}

