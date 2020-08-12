---
description: 그리드의 Multi Update 정보에서 열 구분자를 지정하는 속성이다.
---

# colsep

그리드의 Multi Update 정보에서 열 구분자를 지정하는 속성이다. Multi Update 기능은 그리드 내의 정보를 사용자가 추가,수정,삭제 등을 하였을 때 그 내용을 관리하는 기능이다. \(TrustForm4.0 가이드 &gt; 컨트롤 &gt; grid 컨트롤 &gt; Multi Update 참고\)

colsep 속성은 이 Multi Update 기능 중 getUpdateData\(\) 와 같은 함수를 사용하였을 때 반환되는 문자열에서 열 구분자를 설정하는 속성이다.

이 속성을 설정하지 않으면 기본으로 ^ 가 구분자로 지정된다.

```javascript
<datagrid id="datagrid1" nodeset="/root/grid" class="datagridClass" 
caption="caption1^caption2^caption3" colsep="^" mergecellsfixedrows="bycolrec" 
rowsep="|" style="left:30px; top:30px; width:350px; height:150px; "> 
```

