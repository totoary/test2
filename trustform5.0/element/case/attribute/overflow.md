---
description: case 컨트롤에서 자식 컨트롤들이 차지하는 영역에 대한 표현 방법을 설정하는 속성이다.
---

# overflow

## DESCRIPTION

*visible : 모든 컨트롤들이 화면에 표시될 수 있도록 case 의 영역을 확장하거나 축소한다.
*hidden : 자식 컨트롤들이 case 의 영역을 벗어나면 영역을 벗어난 컨트롤들은 화면에 보이지 않는다.
*scroll : 자식 컨트롤들이 case 의 영역을 벗어나면 스크롤바를 보여준다. 이 속성을 설정하지 않으면 기본으로 scroll 로 설정한 것과 같이 동작한다.

{% hint style="info" %}
case 의 overflow 속성을 설정할 경우 case 는 switch 컨트롤 하위에 존재하는 엘리먼트이기 때문에 switch 컨트롤 영역에서 벗어나면 overflow 속성을 visible 로 설정해도 switch 영역에 의해 벗어난 부분은 화면에 보여지지 않는다.
{% endhint %}

## VALUES

visible / hidden / scroll(default)

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<case id="case2" overflow="hidden"> 
```
{% endcode %}

