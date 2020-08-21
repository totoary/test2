---
description: checkbox 컨트롤의 tootip 내용을 설정한다.    
---

#   hint                       

## DESCRIPTION

마우스를 checkbox 컨트롤에 올려놓고 있으면 hint 에 설정 해 놓은 내용이 마우스 포인터 옆에 툴팁형태로 보인다.

{% hint style="info" %}hint를 동적으로 바꾸기 위해서는 hint property를 사용한다.
hint 속성을 줄 경우 이벤트를 설정할 수 있다.
hint 속성은 다른 attribute처럼 Element안에 속성형태로 설정되는 것이 아니라
caption 컨트롤 하위에 별도의 Element 형태로 추가된다.{% endhint %}   

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<hint> 

      <![CDATA[ 이곳에 ToolTip의 내용을 입력하세요 ]]> 

</hint>  
```
{% endcode %}