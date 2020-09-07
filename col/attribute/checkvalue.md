---
description: null
---

# checkvalue

## DESCRIPTION

type attribute 가 "checkbox" 또는 "radio" 일 때 체크되었거나 체크 해제 되었을 때 인스턴스에 저장 할 값을 설정하는 속성이다.

datagrid 의 col 은 checkbox 나 radio 가 되어도 select 계열의 checkbox 컨트롤이나 radio 컨트롤처럼 itemset 을 가지는 것이 아니라 bool 컨트롤과 같이 체크가 되거나 해제가 되었을 때 저장되는 값\(checkvalue\) 를 가지게 된다.

checkvalue 에는 선택 되었을 때와 해제 되었을 때 인스턴스에 저장 할 두개의 값을 , \(쉼표\) 를 구분자로 사용하여 설정하면 된다. 예\) T,F 또는 Yes,No

설정하지 않을 시 디폴트로는 true,false 가 설정이 되어서 체크가 되면 인스턴스에 true 가 저장되고 해제되면 false 가 저장된다. 쉼표가 두개 이상 들어가거나 유효하지 않은 값이 설정 된 경우에도 디폴트\(true,false\)로 설정이 된다.

## VALUES

true,false / 1,0 / Y,N / M,F

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col checkvalue="1,0" ref="col1" type="checkbox"/>
```
{% endcode %}

