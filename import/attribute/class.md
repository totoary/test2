---
description: import 컨트롤에 스타일을 적용하기 위해 스타일시트 클래스를 설정하거나 클래스 아이디를 설정한다.
---

# class

## DESCRIPTION

class = "aaa bbb" 와 같이 띄어쓰기가 들어간 형식은 지원하지 않는다.

스타일시트는 CSS 창에서 외부 css 파일을 연결하거나 로컬 css 를 추가하여 사용할 수 있다.

이 속성은 설정하지 않으면 class 는 설정되지 않는다

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<import id="import1" class="mixClass" src="class_import.xrw" 
style="left:145px; top:125px; width:200px; height:150px; "/>
```
{% endcode %}

