---
description: datagrid 컨트롤의 disabled(비활성화) 상태를 설정하는 속성이다.
---

# disabled

## DESCRIPTION

컨트롤이 disabled 상태가 되면 datagrid 내의 모든 셀들이 readonly 상태가 되며 모든 UI 에 관련된 이벤트를 받지 못하게 된다. \(UI 이벤트 : mouse, keyboard, scroll, focus/navindex 관련 이벤트\)

이 속성을 설정하지 않으면 기본값은 false 이다.

{% hint style="info" %}
 datagrid / multilinegrid 의 disabled 속성을 true 로 설정하게 되면 컨트롤 자체가 readonly 상태가 되지만, 행 추가/삭제 또는 열 추가/삭제 와 같이 외부에서 조작이 가능한 동작을 수행하면 datagrid / multilinegrid 에 정상적으로 반영된다. 

단, datagrid / multilinegrid 가 비활성화\(disabled\) 상태일 때 컨트롤을 조작하는 것은 보장하지 않으므로 주의해서 사용해야 한다.
{% endhint %}

{% hint style="info" %}
datagrid / multilinegrid 의 disabled 속성을 true 로 설정하게 되면 컨트롤 자체가 readonly 상태가 되지만, 행 추가/삭제 또는 열 추가/삭제 와 같이 외부에서 조작이 가능한 동작을 수행하면 datagrid / multilinegrid 에 정상적으로 반영된다. 단, datagrid / multilinegrid 가 비활성화

\(disabled\) 상태일 때 컨트롤을 조작하는 것은 보장하지 않으므로 주의해서 사용해야 한다.
{% endhint %}

Once you're strong enough, save the world:

{% code title="hello.sh" %}
```bash
# Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```
{% endcode %}



