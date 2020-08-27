---
description: textarea 컨트롤에 입력 가능한 최대 자리 수를 byte 로 설정하는 속성이다.
---

# maxbyte

## DESCRIPTION

maxbyte 를 지정하면 maxbyte 만큼 값이 입력되고, 다음 컨트롤로 포커스가 이동하고 입력 값은 음수가 아닌 양수 값으로 설정해준다. 영문 또는 숫자를 입력할 경우 maxbyte 에 설정한 값 만큼 입력이 되고, 한글을 입력할 경우 "maxbyte 에 설정한 값을 반으로 나눈 값만큼 입력이 된다. 만약 설정한 값이 홀수 일 경우 소수부분은 무시한다.

예로 maxbyte 를 5로 설정했을 때 영문과 숫자는 5자리가 입력되지만, 한글은 두글자 입력 후 더이상 입력되지 않는다.

format, mask 등과 같은 속성이 함께 설정되어 있을 경우 maxbyte 의 길이체크에 포함된다. 예를 들어 maxbyte 속성을 5로 설정했을 경우 @format="yyyy-mm-dd" 이면 "2020-"까지만 입력된다.

{% hint style="info" %}
@maxbyte=2 인 textarea 컨트롤에 한글과 영문\(또는 숫자\)을 조합하여 입력할 때 한글 한자리만 입력되거나, 영문 1byte 입력 후 입력되지 않는다.
{% endhint %}

{% hint style="info" %}
maxbyte 속성과 maxlength 속성이 함께 설정되어 있을 경우에는 maxbyte 속성이 무시되고 maxlength 속성 값이 설정된다.
{% endhint %}

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<textarea id="textarea5" ref="/root/sample/Basic/maxlength" navindex="2" maxlength="5" style="left:129px; top:69px; width:100px; height:50px; "/> 
```
{% endcode %}

