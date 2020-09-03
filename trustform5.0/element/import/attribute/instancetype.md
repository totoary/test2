---
description: import 된 xrw 문서의 인스턴스 처리방식을 지정하는 속성이다.
---

# instancetype 

## DESCRIPTION

append, merge, replace 로 설정이 가능하다.
설정한 instancetype 에 따른 동작은 다음과 같다.

* append : import 된 문서의 인스턴스가 현재 문서의 인스턴스 마지막 부분에 추가한다.
* merge : import 된 문서의 인스턴스 중에 현재 문서와 동일한 인스턴스가 존재 한다면 두 인스턴스를 병합한다. 그 외의 경우는 'append' 로 처리된다.
* replace : import 된 문서의 인스턴스 중에 현재 문서와 동일한 인스턴스가 존재 한다면 현재 문서의 인스턴스를 import 된 문서의 인스턴스로 교체한다. 그 외의 경우는 'append' 로 처리된다.   

## VALUES

append / merge / replace

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<import id="import2" src="instancetype_import02.xrw" instancetype="merge" 
style="left:2px; top:3px; width:250px; height:95px; "/> 
```
{% endcode %}
