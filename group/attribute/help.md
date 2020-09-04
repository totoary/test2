---
description: group 컨트롤에 포커스를 주고 F1 을 누르면 알림창 형태로 해당 내용이 보여진다.
---

# help

## DESCRIPTION

디자이너에서 attribute 창에 help 속성을 설정해 주면 내용이 알림창 형태로 보여진다.

F1 을 누르면 xforms-help 이벤트가 발생하는데, group 하위의 다른 컨트롤에서 F1 을 누르면 xforms-help 이벤트가 버블링을 타고 group 까지 전달이 되기때문에 group 에 help 속성을 설정 해두면 문서 내 어느곳이나 포커스가 있는 상태에서 F1 을 누르면 알림창이 뜬다.

{% hint style="info" %}
help 속성은 다른 attribute 처럼 Element 안에 속성형태로 설정되는 것이 아니라, group 컨트롤 하위에 별도의 Element 형태로 추가가 된다.
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<help>
    <![CDATA[ 이곳에 Help의 내용을 입력하세요 ]]> 
</help>
```
{% endcode %}

