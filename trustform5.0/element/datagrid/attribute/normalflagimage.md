---
description: Multi Update 상태 중 normal 상태일 때 rowheader 에 표시할 이미지를 설정하는 속성이다. 
---

#  normalflagimage           

## DESCRIPTION

Multi Update 상태 중 normal 상태일 때 rowheader 에 표시할 이미지를 설정하는 속성이다.
normal 상태는 그리드의 행이 수정,삭제,추가 되지 않은 보통상태를 의미한다.
이 속성은 rowheader attribute 가 update 일 때만 동작을 한다.

Multi Update 의 자세한 사용법은
TrustForm5.0 가이드 > 컨트롤 > grid 컨트롤 > Multi Update 를 참고.

이 속성을 설정하지 않으면 디폴트 normal 플래그 이미지가 설정된다. (회색 동그라미 마크)        
   
## VALUES

Picture Files (bmp.dib.emf.gif.ico.jpg.wmf)|*.bmp;*.dib;*.emf;*.gif;*.ico;*.jpg;*.wmf|BMP (*.bmp)|*.bmp|DIB (*.dib)|*.dib|EMF (*.emf)|*.emf|GIF (*.gif)|*.gif|ICO (*.ico)|*.ico|JPG (*.jpg)|*.jpg|WMF (*.wmf)|*.wmf|All Files (*.*)|*.*||

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="memberGrid" nodeset="/root/memberSample/gridData/member" caption="Name^Gender^Level" colsep="^" deleteflagimage="delete.gif" insertflagimage="insert.gif" mergecellsfixedrows="bycolrec" normalflagimage="normal.gif" rowheader="update" rowsep="|" updateflagimage="update.gif" style="left:50px; top:260px; width:350px; height:295px; "> 
```
{% endcode %}



