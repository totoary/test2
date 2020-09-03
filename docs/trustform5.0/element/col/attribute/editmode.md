---
description: col 의 type 이 combo 일때 콤보에 검색, 입력과 같은 기능을 설정하는 속성 
---

# editmode

## DESCRIPTION

* input : 콤보에 입력 기능을 사용.  아이템 리스트 에서 아이템을 선택하지 않고 콤보 컨트롤에 직접 키보드로 입력 할 수 있다. 직접 입력한 값과 같은 label 을 가지는 아이템이 존재하지 않는다고해도 입력이 가능하다.
* search : 콤보에 검색 기능을 사용.  콤보에 직접 키보드로 입력을 하면 입력한 문자 혹은 문자열과 완전히 일치하거나 그것으로 시작하는 아이템이 리스트에서 선택표시가 된다. 만약 입력한 값과 같은 label 값을 가지는 아이템이 없다면 입력한 값은 무시되고, 이전에 선택된 값이 보여진다.
* inputsearch : 콤보 컨트롤에 검색기능과 입력기능을 사용한다.  search 로 설정 했을 때와 비슷한 기능이다. 다른점은 search 기능 사용시 입력한 값으로 시작하거나 같은 label 을 가지는 아이템이 없을 경우 입력값이 무시되는 반면, inputsearch 는 아이템 리스트 에 존재하지 않는 값도 입력이 된다는 점이다.

{% hint style="info" %}
search 로 설정이 되어 있을 때, 아이템 리스트에 존재하지 않는 값을 입력할 경우에는 이전에 선택되어 있는 값으로 보여지도록 설정되어 있다.   
{% endhint %}
## VALUES

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<col editmode="search" ref="a" type="combo"/> 
```
{% endcode %}
