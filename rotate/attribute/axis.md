# axis

### description:컨트롤 회전의 중심축을 설정하는 속성이다.

## axis

### DESCRIPTION

x를 선택하면 가로축으로 회전하고, y를 선택하면 세로축으로 회전한다.

### VALUES

x / y

### EXAMPLE

{% code title="\[Static\]" %}
```markup
<animation id="ani1">
    <rotate id="rotate1" during="1000" frame="30" target="input1" count="1" axis="y"/>
</animation>
```
{% endcode %}

