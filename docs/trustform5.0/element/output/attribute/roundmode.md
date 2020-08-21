<<<<<<< HEAD
---
description: 반올림, 올림, 버림 등을 수행하도록 설정하는 속성이다     
---

#   roundmode                       

## DESCRIPTION

roundmode 속성을 설정할 경우에는 roundposition 과 format 을 함께 설정하여 사용해야 한다.
format 은 일반 숫자의 경우 # 이라고만 지정해 주거나 소수점이 있는 숫자의 경우 #.# 과 같이 지정하면 된다. 

* round : 반올림 수행
* ceil : 올림 수행
* floor : 버림 수행
  
## VALUES

round / ceil / floor

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="applyValue" ref="/root/applyValue" format="#.#" roundmode="round" roundposition="-2" style="left:170px; top:85px; width:140px; height:20px; "/>  
```
{% endcode %}
=======
---
description: 반올림, 올림, 버림 등을 수행하도록 설정하는 속성이다     
---

#   roundmode                       

## DESCRIPTION

roundmode 속성을 설정할 경우에는 roundposition 과 format 을 함께 설정하여 사용해야 한다.
format 은 일반 숫자의 경우 # 이라고만 지정해 주거나 소수점이 있는 숫자의 경우 #.# 과 같이 지정하면 된다. 

* round : 반올림 수행
* ceil : 올림 수행
* floor : 버림 수행
  
## VALUES

round / ceil / floor

## EXAMPLE

{% code title="\[Static\]" %}
```markup
<input id="applyValue" ref="/root/applyValue" format="#.#" roundmode="round" roundposition="-2" style="left:170px; top:85px; width:140px; height:20px; "/>  
```
{% endcode %}
>>>>>>> eaecbff44ad16a728baa64cf76485a2e44cd3f57
