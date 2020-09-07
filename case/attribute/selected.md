---
description: switch 컨트롤에서 case 컨트롤의 선택된 상태를 설정하는 속성이다.
---

# selected

## DESCRIPTION

switch 컨트롤에서 case 컨트롤의 선택된 상태를 설정하는 속성이다. 디자인시 switch 컨트롤에서 여러 개의 case 에서 하나를 선택하면 selected 속성이 true 로 설정되고, 실행하면 selected 가 true 인 case 를 화면에 보여준다.

디자인 시점에 switch 컨트롤을 생성하면 자동으로 생성되는 case 컨트롤의 selected 속성이 true 로 설정되고, 여러 case 가 존재할 때, 하나의 case 를 선택하면 선택된 case 의 selected 속성이 자동으로 true 가 설정된다. 그리고 폼을 실행하기 전에 선택하여 selected 가 true 로 설정된 case 를 실행시 화면에 보여준다.

{% hint style="info" %}
을 실행하기 전에 선택된 case 가 실행시점에 화면에 나타나므로, 여러개의 case 컨트롤안에 컨트롤을 생성할 때 컨트롤을 생성한 후, 폼을 실행하기전에 화면에 보여줄 case 컨트롤을 선택한 후 폼을 실행해야 한다.
{% endhint %}

## VALUES

true / false

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<case id="case1" selected="true" >
```
{% endcode %}

