# step

### description:스크롤 버튼을 눌렀을 때 스크롤이 움직이는 정도를 지정하는 속성이다.

## step

### DESCRIPTION

디자인 시점에서 scrollbar 에 대한 속성을 설정 할 수 없기 때문에 attribute property 를 이용하여 page 속성 값을 변경해야 한다.

{% hint style="info" %}
* scroll 은 Element 의 vscroll 또는 hscroll 로 접근한다.   
{% endhint %}

### EXAMPLE

{% code title="\[Dynamic\]" %}
```markup
<script ev:event="DOMActivate" type="javascript">
    <![CDATA[
        textarea.vscroll.attribute("step") = "200";
    ]]>
</script>
```
{% endcode %}

