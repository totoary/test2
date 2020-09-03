---
description: radio 컨트롤의 tootip 의 내용을 설정한다.
---

# hint

## DESCRIPTION

마우스를 radio 컨트롤에 올려놓고 있으면 hint 에 설정 해 놓은 내용이 마우스 포인터 옆에 힌트로 뜬다. 이 속성은 설정하지 않으면 hint 는 설정이 되지 않는다.

hint 속성을 줄 경우 이벤트를 설정할 수 있다.  
이벤트를 설정하면 해당 이벤트가 발생 했을때 hint의 내용이 tooltip의 형태로 뜬다.

{% hint style="info" %}
hint 속성은 다른 attribute 처럼 element 안에 속성형태로 설정되는 것이 아니라 combo 컨트롤 하위에 별도의 element 형태로 추가가 된다
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<hint> 

      <![CDATA[ 이곳에 ToolTip의 내용을 입력하세요 ]]> 

</hint>
```
{% endcode %}

