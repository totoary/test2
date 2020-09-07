---
description:서버로부터 받은 데이터의 처리 방식을 설정하는 속성이다.
---

# add

## DESCRIPTION

*""(설정안함):resultref 경로와 동일한 depth 있는 기존 데이터를 삭제하고 받은 데이터를 추가한다.
*top:서버에서 받은 데이터를 resultref 경로와 동일한 depth 의 위쪽에 누적한다.
*bottom:서버에서 받은 데이터를 resultref 경로와 동일한 depth 의 아래쪽에 누적한다.

## VALUES

""(설정안함) / top / bottom

## EXAMPLE
{% code title="\[Static\]" %}
```markup
<submission id="getAddressBook" action="http://localhost:8080/TFjsp/submission_attribute1.jsp" mediatype="application/x-www-form-urlencoded" method="post" add="bottom" resultref="/root/res"/> 
```
{% endcode %}