---
description:radio 가 선택 되었을 때의 이미지를 설정하는 속성 
---

# selectimage 

## DESCRIPTION

type attribute 가 "radio" 이고 선택되어 있는 상태일 때 보여질 이미지를 설정하는 속성이다.
이미지의 경로는 절대경로 또는 상대경로를 설정한다.

type attribute 가 "radio" 가 아닐 때에는 설정해도 동작하지 않는다.
선택이 해제되어 있는 상태일 때 보여질 이미지는 unselectimage attribute 로 설정할 수 있다.
   
## VALUES
Picture Files (bmp.dib.emf.gif.ico.jpg.wmf)|*.bmp;*.dib;*.emf;*.gif;*.ico;*.jpg;*.wmf|BMP (*.bmp)|*.bmp|DIB (*.dib)|*.dib|EMF (*.emf)|*.emf|GIF (*.gif)|*.gif|ICO (*.ico)|*.ico|JPG (*.jpg)|*.jpg|WMF (*.wmf)|*.wmf|All Files (*.*)|*.*|| 

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col selectimage="image.gif" ref="col1" type="radio"/> 
```
{% endcode %}
