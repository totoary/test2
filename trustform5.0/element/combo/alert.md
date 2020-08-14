---
description: validation에 실패 했을 경우 해당내용을 alert창 형태로 보여준다.
---

# alert

## Getting Super Powers

Becoming a super hero is a fairly straight forward process:

```
$ give me super-powers
```

{% hint style="info" %}
 Super-powers are granted randomly so please submit an issue if you're not happy with yours.
{% endhint %}

Once you're strong enough, save the world:

{% code title="hello.sh" %}
```bash
# Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```
{% endcode %}

## DESCRIPTION

alert속성을 줄 경우 이벤트를 설정할 수 있다.

이벤트를 설정하면 해당 이벤트가 발생 했을때 alert에 설정한 내용이 alert창 형태로 보여진다.

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<alert ev:event="onclick">
      <![CDATA[ 이곳에 내용을 입력하세요 ]]>
</alert>
```
{% endcode %}
