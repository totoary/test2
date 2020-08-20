---
description: 콤보 리스트에 label 값과 value 값을 동시에 보이도록 설정한다.
---

# showvalue

## DESCRIPTION

* true : label 값과 value 값을 동시에 보임
* false : label 값만 보임

이 속성을 설정하지 않으면 기본으로 false 로 동작한다.

{% hint style="info" %}
이 속성은 direction, rows, cols 속성과 함께 사용될 수 없다. 

showvalue 속성을 true 로 설정하면 combo list 에 label 값과 value 값이 함께 보여지도록 두 개의 컬럼으로 구성되어 나타나야 하므로 rows 와 cols 속성은 값을 주어도 설정되지 않는다.

또한 이 label 값과 value 값을 각각 하나의 item 으로 구성되고 rows 와 cols 속성을 지원하지 않기 때문에 direction 을 설정하면 두 속성은 충돌을 일으켜 예상치 못한 동작을 한다.

showvalue 를 true 로 설정한 경우 focusIndex 는 짝수로 증가하게된다. 이유는 콤보 리스트 상의 label 과 value 를 각각 하나의 아이템으로 생성하기 때문이다.
{% endhint %}

## E

