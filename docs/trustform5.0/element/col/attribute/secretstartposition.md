---
description:secret 마크가 시작되는 곳의 인덱스를 설정하는 속성이다.
---

# secretstartposition 

## DESCRIPTION

인덱스는 0부터 시작한다.

그리드의 셀의 내용을 secret mark ( * 과 같은 문자) 로 표현할 때 secret mark 를 시작할 위치를 설정할 수 있다.

예를 들어 2번째 문자부터 5번째 문자까지만 secret mark 로 표시하려면 secretstartposition 을 2 로 설정하고 secretendposition 을 6 으로 설정하면 된다. 
secretendposition 을 6으로 설정하는 이유는 secretendposition 에 지정된 위치의 문자는 포함하지 않기 때문이다

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col ref="number" secretendposition="5" secretmark="#" secretstartposition="0" type="input"/> 
```
{% endcode %}
