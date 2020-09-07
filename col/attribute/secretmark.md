# secretmark

### description:secret 마크를 설정하는 속성

## secretmark

### DESCRIPTION

secretstartposition 과 secretendposition 속성들로 그리드의 셀을 secret 컨트롤과 같이 사용할때 기본으로 설정된 secret mark \(\*\) 를 다른 기호로 사용하고 싶을 때 설정한다.

이 속성을 설정하지 않으면 기본으로 \* 문자가 secret mark 로 사용된다.

### EXAMPLE

{% code title="\[Static\]" %}
```markup
<col ref="password" secretmark="$" secretstartposition="0"/>
```
{% endcode %}

