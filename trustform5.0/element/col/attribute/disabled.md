---
description: 열의 비활성화 상태를 설정하는 속성 
---

# disabled 

## DESCRIPTION

해당 컬럼의 초기 비활성화 상태를 설정하는 속성이다.
이 속성이 true 로 설정되어 있는 열은 초기 로딩 시점에 비활성화가 되어 사용자가 수정을 할 수 없게 된다.

이 속성을 설정하지 않으면 기본으로 false 로 설정한 것과 같이 활성화가 된다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 col 의 disabled 를 동적으로 제어하기 위해서는 colDisabled property 를 사용한다.   
{% endhint %}

## VALUES

true / false(default)

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col disabled="true" ref="b" type="input"/> 
```
{% endcode %}
