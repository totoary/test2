# page

### description:스크롤바를 클릭했을 때 스크롤이 되는 정도를 나타내는 속성이다.

## page

### DESCRIPTION

attribute property 를 이용하여 스크롤 되는 정도를 변경 할 수 있지만 정상동작을 보장하진 않으므로, 단지 스크롤바의 스크롤 되는 정도를 얻고자 할때에만 attribute property 를 사용하여 접근하기를 권장한다.

{% hint style="info" %}
* scroll 은 Element 의 vscroll 또는 hscroll 로 접근한다.   
{% endhint %}

### EXAMPLE

{% code title="\[Dynamic\]" %}
```markup
<script ev:event="DOMActivate" type="javascript">
    <![CDATA[
        body.vscroll.attribute("page") = 100;
    ]]>
</script>
```
{% endcode %}

