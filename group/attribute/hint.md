---
description: group   컨트롤의 tootip 내용을 설정한다.
---

# hint

## DESCRIPTION

마우스를 group 컨트롤에 올려 놓고 있으면 hint 에 설정한 내용이 마우스 포인터 옆에 툴팁형태로 보여진다.

group 안에 포함되어 있는 컨트롤들에 hint 를 설정할 경우 group 안에 있는 컨트롤에서는 컨트롤에 설정한 hint 가 나타난다.

{% hint style="info" %}
hint를 동적으로 바꾸기 위해서는 hint property를 사용한다. hint 속성은 다른 attribute 처럼 Element 안에 속성 형태로 설정되는 것이 아니라 group 컨트롤 하위에 별도의 Element 형태로 추가가 된다.
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<hint> 

      <![CDATA[ 이곳에 ToolTip의 내용을 입력하세요 ]]> 

</hint>
```
{% endcode %}

