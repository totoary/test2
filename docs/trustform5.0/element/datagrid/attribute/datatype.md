---
description: 그리드를 일반 그리드로 사용할 지 라이트 그리드로 사용할지 설정하는 속성이다.
---

# datatype

## DESCRIPTION

그리드를 일반 그리드\(xml\) 로 사용하면 인스턴스를 사용하게 되고, 라이트 그리드\(delimeter\) 로 사용하면 기본적인 인스턴스는 맵핑이 되어 있어야 하지만, 인스턴스를 실제 사용하지는 않게 된다.

라이트 그리드의 자세한 사용법은 TrustForm5.0 가이드 &gt; 컨트롤 &gt; grid 컨트롤 &gt; Light grid 사용하기 참고.

이 속성은 설정하지 않으면 기본으로 xml\(인스턴스를 사용하는 일반 그리드\) 로 설정이 된다

## **VALUES**

* **xml\(default\) / delimeter**

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid2" nodeset="/root/g" caption="caption1^caption2^caption3" 
colsep="^" datatype="delimeter" mergecellsfixedrows="bycolrec" rowsep="|" 
style="left:420px; top:35px; width:350px; height:150px; "> 
```
{% endcode %}

