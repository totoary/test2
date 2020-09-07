# editable

### description:열의 에디트 가능한 상태를 설정하는 속성

## editable

### DESCRIPTION

col 타입이 input, input\_date, input\_button 인 열의 에디트 가능한 상태를 설정하는 속성이다. editable 을 true 로 설정하면 input 의 값을 에디트상태에서 편집하여 수정할 수 있고, false 로 설정하면 input 컨트롤의 값을 복사할 수는 있지만, 에디트상태에서 편집하여 수정할 수 없는 상태로 설정한다.

이 속성을 설정하지 않으면 기본으로 true 가 설정된다. \(에디트 가능상태\)

{% hint style="info" %}
disabled 상태는 모든 UI 에 관련된 이벤트를 받지 못하게 되지만, editable 설정은 단지 컨트롤 값을 편집이 되지 않는 상태이다.
{% endhint %}

### VALUES

true\(default\) / false

### EXAMPLE

{% code title="\[Static\]" %}
```markup
<col ref="password" secretstartposition="0" type="input" editable="false"/>
```
{% endcode %}

