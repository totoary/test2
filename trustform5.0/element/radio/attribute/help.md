---
description: radio 컨트롤의 tootip 내용을 설정한다.  
---

#   help                       

## DESCRIPTION

마우스를 radio 컨트롤에 올려놓고 있으면 hint 에 설정해 놓은 내용이 마우스 포인터 옆에 툴팁형태로 보인다.

hint 를 동적으로 바꾸기 위해서는 hint property 를 사용한다.

{% hint style="info" %}help 속성은 다른 attribute 처럼 Element 안에 속성 형태로 설정되는 것이 아니라, 
radio 컨트롤 하위에 별도의 Element 형태로 추가가 된다.{% endhint %}   

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<help>
	<![CDATA[ 이곳에 Help의 내용을 입력하세요 ]]> 
</help>  
```
{% endcode %}