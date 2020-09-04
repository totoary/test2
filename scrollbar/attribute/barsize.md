# barsize

### description:스크롤바의 크기를 저장하고 있는 속성

## editmenu

### DESCRIPTION

attribute property 를 이용하여 scrollbar 의 크기를 변경할 수 있지만 정상동작을 보장하지 않으므로, 단지 스크롤바의 크기를 얻고자 할때에만 attribute property 를 사용하여 접근하기를 권장한다.

{% hint style="info" %}
* scroll 은 Element 의 vscroll 또는 hscroll 로 접근 가능한다.  
{% endhint %}

### EXAMPLE

{% code title="\[Dynamic\]" %}
```markup
<script ev:event="onscroll" type="javascript">
    <![CDATA[                                    
            alert(body.vscroll.attribute("barsize"));                        
    ]]>
</script>
```
{% endcode %}

