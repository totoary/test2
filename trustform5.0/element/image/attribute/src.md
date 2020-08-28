---
description: img 컨트롤에 보여줄 이미지 파일의 경로를 설정해준다.
---

# src

## DESCRIPTION

디자인 시점에 img 컨트롤을 생성하면 화면에 보여줄 이미지 파일 경로를 설정하는 dialog 창이 나타나고, 이 창에서 이미지 파일의 src 경로를 설정해준다.

src 속성으로 설정한 경로는 절대경로 또는 상대경로 둘 다 설정이 가능하고, src property 를 사용하여 설정한 src 경로를 반환할 수 있다.
{% hint style="info" %}
src 속성은 디자인 시점에 img 에 설정할 이미지 파일의 경로를 설정해 주는 것이고, 스크립트 상에서 img 의 src property 를 사용하여 변경할 수 있다. 
{% endhint %}
## VALUES

Picture Files (bmp.dib.emf.gif.ico.jpg.wmf)|*.bmp;*.dib;*.emf;*.gif;*.ico;*.jpg;*.wmf|BMP (*.bmp)|*.bmp|DIB (*.dib)|*.dib|EMF (*.emf)|*.emf|GIF (*.gif)|*.gif|ICO (*.ico)|*.ico|JPG (*.jpg)|*.jpg|WMF (*.wmf)|*.wmf|All Files (*.*)|*.*||

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<img id="img1" src="src_image.jpg" style="left:80px; top:105px; width:500; height:187; background-stretch:stretch; "/> 
```
{% endcode %}
