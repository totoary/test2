---
description: grid의 combo col 의 combo mark를 항시 보여주는 속성
---

# showcombomark

## DESCRIPTION

이 속성이 추가되면 grid의 cell 이 선택되지 않은 상황에서도 기본적으로 combo mark가 보인다. css를 이용하여 설정이 가능하며 grid의 combo mark style 또한 css로 설정이 가능하다.

showcombomark="true" 이면 grid 와 multilinegrid 의 combo mark 가 언제나 보이게 된다.

css 적용 시 grid combo 에서 combo 활성화 전에 보이는 버튼과 실제 combo 활성화 나타나는 버튼은 다르다. 그러므로 각각 css 를 적용시켜야 한다.

gridcombo &gt; combobutton { background-color:red; border-style:none; background-image:./btnGrdContFind\_n.gif; }

col\[type="combo"\] &gt; gridbutton { background-color:red; border-style:none; background-image:./btnGrdContFind\_n.gif; }

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col ref="a" type="combo" showcombomark="true">
```
{% endcode %}

