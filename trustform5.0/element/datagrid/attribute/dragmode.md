---
description: 컨트롤에서 드래그를 할 수 있도록 설정하는 속성이다.
---

# dragmode

## DESCRIPTION

dragmode 를 true 로 설정하면 사용자가 마우스로 datagrid 컨트롤에서 드래그 동작을 할 수 있도록 설정만 해주는 것이다. 실제로 컨트롤의 값을 dropData 에 넣거나, 그 외 다른 동작을 수행 하고 싶은 경우에는, ondragstart 이벤트에서 event.dropData 에 데이터를 넣어주거나 수행하고 싶은 동작을 수행하면 된다.

\(주의\) drag & drop 은 application view 에서는 동작하지 않고 IE 에서만 동작한다.

* Drag & Drop 의 자세한 사용법은  TrustForm4.0 &gt; Drag&Drop 사용하기  참고.

이 속성을 설정하지 않으면 기본으로 false 로 설정된다.

## VALUES

* true / false\(default\)

## Once you're strong enough, save the world:

{% code title="hello.sh" %}
```bash
# Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```
{% endcode %}



