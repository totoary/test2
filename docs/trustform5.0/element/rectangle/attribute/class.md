---
description:스타일시트 클래스를 설정하거나 클래스 아이디를 설정하는 속성 
---

# class

## DESCRIPTION

rectangle 컨트롤에 스타일을 적용하기 위해 스타일시트 클래스를 설정하거나 클래스 아이디를 설정한다.
class = "aaa bbb" 와 같이 띄어쓰기가 들어간 형식은 지원하지 않는다.

스타일시트는 CSS 창에서 외부 css파일을 연결하거나 로컬 css 를 추가할 수 있다. 

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<shape id="rectangle" class="rectangleStyle" appearance="rectangle" style="left:80px; top:240px; width:275px; height:255px; "/> 
```
{% endcode %}