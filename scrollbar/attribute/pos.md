# pos

### description:스크롤의 현재 위치를 설정하는 속성이다.

## pos

### DESCRIPTION

scrollbar 는 디자인 시점에서 속성을 설정할 수 없기 때문에 attribute property 를 이용하여 설정해야한다.

{% hint style="info" %}
* scroll 은 Element 의 vscroll 또는 hscroll 로 접근한다.  
{% endhint %}

### EXAMPLE

{% code title="\[Dynamic\]" %}
```markup
<script ev:event="DOMActivate" type="javascript">
    <![CDATA[
        textarea.vscroll.attribute("pos") = "100";
    ]]>
</script>
```
{% endcode %}

