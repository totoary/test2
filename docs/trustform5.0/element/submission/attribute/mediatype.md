---
description:서버와 통신하는 데이터의 형식을 지정하는 속성이다. 
---

# mediatype 

## DESCRIPTION
*application/x-www-form-urlencoded : submission 을 수행할 때 일반적으로 사용되는 데이터 타입이며 Form 에 담긴 데이터는 RFC1738 문서에  규약된 대로
                                                       인코딩 되어 서버에 전달된다.
주로 일반적인 XML 통신에 사용된다.
  
*multipart/form-data : 'application/x-www-form-urlencoded' 으로 설정할 경우 많은 양의 바이너리 데이터나 ASCII 문자가 아닌 데이터를 전송할 경우 비효율적이다.  
                                때문에 파일이나 ASCII 문자가 아닌 데이터를 서버로 전송할때 multipart/form-data 방식을 이용한다.
* 주로 파일을 업로드를 할때 사용된다. / 파일 업로드시에는 서버에 업로드용 서버 유틸리티를 따로 설치해야한다.

*application/xml : 서버와 통신할때 XML 문서를 주고 받음으로써 통신하도록 한다.  바이너리 데이터(파일)도 포함 할 수 있다.

*text/xml : application/xml 과 동일하지만 바이너리 데이터를 포함 할 수 없다.

*application/json
*text/json

## VALUES
application/x-www-form-urlencoded / multipart/form-data / application/xml / text/xml / application/json / text/json
## EXAMPLE

{% code title="\[Static\]" %}
```markup

```
{% endcode %}