---
description: datagrid 컨트롤의 tooltip 의 내용을 설정한다.

---

# hint

## DESCRIPTION

마우스를 datagrid 에 올려놓고 있으면 hint 에 설정한 내용이 마우스포인터 옆에 툴팁형태로 보인다. 

datagrid 컨트롤의 tooltip attribute 와 함께 설정이 되어 있을 경우 tooltip 이 우선 적용이 된다. (적용 우선순위 : tooltip > hint)
즉, tooltip 이 true 이고 hint 속성에 값이 설정이 되어있는 경우, 데이터 셀에 마우스를 올려놓으면 tooltip 이 적용이 되고, 
데이터 구간이 아닌 곳에 마우스를 올려 놓으면 hint 속성에 설정한 값이 나타난다.

* hint 를 동적으로 바꾸기 위해서는 hint property 를 사용한다.

참고) hint 속성은 다른 attribute 처럼 Element 안에 속성형태로 설정되는 것이 아니라 datagrid 컨트롤 하위에 별도의 Element 형태로 추가가 된다.  

## EXAMPLE

{% code title="\[Static \]" %}
```bash
<hint> 

      <![CDATA[ 이곳에 ToolTop의 내용을 입력하세요 ]]> 

</hint>

```
{% endcode %}


