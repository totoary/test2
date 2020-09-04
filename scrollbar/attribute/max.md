# max

### description:스크롤이 제일 끝으로 움직였을때의 위치를 저장하는 속성

## max

### DESCRIPTION

attribute property 를 이용하여 scrollbar 의 제일 끝 위치를 변경 할 수 있지만 정상동작을 보장하지 않으므로, 단지 스크롤바의 제일 끝 위치를 얻고자 할때에만 attribute property 를 사용하여 접근하기를 권장한다.

{% hint style="info" %}
* scroll 은 Element 의 vscroll 또는 hscroll 로 접근한다.   
{% endhint %}

### EXAMPLE

{% code title="\[Static\]" %}
```markup
<script ev:event="DOMActivate" type="javascript">
    <![CDATA[
        alert(body.vscroll.attribute("max"));
    ]]>
</script>
```
{% endcode %}

