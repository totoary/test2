---
description: format 적용시 instance 에 마스크 문자를 포함할 지 설정하는 속성     
---

#   mask                       

## DESCRIPTION

format 적용시 instance 에 마스크 문자를 포함할 지 여부를 설정하는 속성이다.

input 컨트롤에 format 이 적용되어 있을 때, 이 속성을 include 로 설정해줄 경우 instance 에는 instance 와 맵핑된 input 컨트롤에 보여지는 것과 똑같이 마스크 문자도 포함되게 된다.
format 이 적용되어 있는 input 컨트롤이 label 과 value 를 항상 똑같이 저장하는 것이다.

이 속성을 설정하지 않으면 exclude 로 설정한 것과 같이 마스크 문자는 인스턴스에 저장되지 않는다.

{% hint style="info" %}mask = include 가 설정되어 있고, maxlenth 가 설정되어 있는경우 값 입력 시 설정된 format 의 포맷문자도 
maxlength 길이로 체크된다.{% endhint %}

{% hint style="info" %}maxlength 체크는 인스턴스값을 가지고 체크를 해주기 때문에 mask = include 가 설정되어 있을 때는 format 을 고려하여 
maxlength 를 설정해 주어야한다.{% endhint %}   
  
## VALUES

exclude / include 

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="Date" ref="/root/Date" format="yyyy/mm/dd" mask="include" style="left:374px; top:49px; width:100px; height:20px; "/>  
```
{% endcode %}

