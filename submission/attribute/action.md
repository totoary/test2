# action

### description:XML 데이터를 요청 할 서버의 URL 을 설정하는 속성이다.

## action

### DESCRIPTION

action 에 설정한 URL 은 요청에 대한 응답으로 XML 형식의 문서를 내려 주어야한다.

{% hint style="info" %}
* 참고 :  file:// 기능을 이용해서 xml 파일로 요청하는 것이 가능함  
{% endhint %}

### VALUES

### EXAMPLE

{% code title="\[Static\]" %}
```markup
<submission id="getAddressBook" action="http://localhost:8080/TFjsp/submission_attribute1.jsp" mediatype="application/x-www-form-urlencoded" method="post" resultref="/root/res"/>
```
{% endcode %}

