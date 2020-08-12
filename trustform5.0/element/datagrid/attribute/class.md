---
description: datagrid 에 스타일을 적용하기 위해 스타일시트 클래스를 설정하거나 클래스 아이디를 설정한다.
---

# class

## DESCRIPTION

class = "aaa bbb" 와 같이 띄어쓰기가 들어간 형식은 지원하지 않는다.

스타일시트는 CSS 창에서 외부 css파일을 연결하거나 로컬 css 를 추가할 수 있다. \(TrustForm5.0 가이드 &gt; CSS 사용하기 참고\)

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<datagrid id="datagrid1" nodeset="/root/grid" class="datagridClass" 
caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" 
rowsep="|" style="left:30px; top:30px; width:350px; height:150px; "> 
```
{% endcode %}

                                         

