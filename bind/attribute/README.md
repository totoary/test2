# attribute

## DESCRIPTION  
디자인시점에서 설정한 bind 의 attribute 값을 실행 시점에서 변경할 때 사용한다.
TrustForm 에서 attribute 는 XML에 정의된 attribute 와 같이 설정이 되고 항상 string 형태로 존재하게 된다.(' 또는 " 로 감싸져야한다) 
그러므로 attribute property 의 get value 와 put value 는 항상 string 이 된다.
특히 계산식(calulate)을 바꾸거나 결과를 저장할 인스턴스(ref)를 동적으로 변경 할때 매우 유용하다.

{% hint style="info" %}
* attribute 는 원칙상 디자인시점에서 설정을 해주는 것이다. 따라서 attribute property 를 이용해 attribute 를 동적으로 변경하는 동작은 보장 할 수 없다. 
{% endhint %}

## SYNTAX 

```scheme
[ String = ] bind.attribute(String name) [ = String ] 
```

{% hint style="info" %}
\[ String = \] bind.attribute\(String name\) \[ = String \]
{% endhint %}

## PARAMETERS 
* eventName\(필수\) : String / 강제적으로 발생 시킬 이벤트 이름
* description\(선택\) : String / 이벤트 설명
* bubbles\(선택\) : Boolean / 버블링을 수행 할 것인지 여부
* defaultAction\(선택\):  Boolean /Default Action 을 수행 할 것인지 여부

## PUT VALUES 
   String : 속성값  

## GET VALUES
  String : 속성값

## EXAMPLE
{% code title="\[javascript\]" %}   
```javascript
<script id="script1" type="javascript" ev:event="DOMActivate">

      <![CDATA[

            body.dispatch("onclick");

      ]]>

</script> 
```

