---
description: 다른 컨트롤에서 드래그 한 값을 현재 컨트롤에 드롭할 수 있도록 해주는 속성이다.
---

# dropmode 

## DESCRIPTION
dropmode 를 true 로 설정했을 때 secret 에 드롭 동작을 하면 event.dropData 에 저장되어 있는 데이터가 secret 에 입력된다.
드롭 시 이외에 다른 동작을 원하는 경우 ondrop 이벤트에서 스크립트를 설정하면 된다.

이 속성은 설정하지 않으면 기본으로 false 가 설정된다,

{% hint style="info" %}
drag & drop 은 application view 에서는 동작하지 않고 IE 에서만 동작한다. 
{% endhint %}

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<secret id="secret2" ref="/root/Basic" dropmode="true" imemode="disabled" 
style="left:93px; top:118px; width:60px; height:20px; "> 
```
{% endcode %}

