# attribute


## DESCRIPTION 
                                                                                
## SYNTAX 

```scheme
[ String = ] bind.attribute(String name) [ = String ] 
```

{% hint style="info" %}
\[ String = \] bind.attribute\(String name\) \[ = String \]
{% endhint %}

* eventName\(필수\) : String / 강제적으로 발생 시킬 이벤트 이름
* description\(선택\) : String / 이벤트 설명
* bubbles\(선택\) : Boolean / 버블링을 수행 할 것인지 여부
* defaultAction\(선택\):  Boolean /Default Action 을 수행 할 것인지 여부

```javascript
<script id="script1" type="javascript" ev:event="DOMActivate">

      <![CDATA[

            body.dispatch("onclick");

      ]]>

</script> 
```

