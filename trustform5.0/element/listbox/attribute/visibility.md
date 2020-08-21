# visibility

### &lt;&lt;&lt;&lt;&lt;&lt;&lt; HEAD

### description: listbox 컨트롤을 화면에 표시할 지를 설정하는 속성이다.

=======

## visibility

> > > > > > > 39a9e6e02e8ed3a645ed43cf175046a74b66407c

#### &lt;&lt;&lt;&lt;&lt;&lt;&lt; HEAD

#### description: checkbox 컨트롤을 화면에 표시할 지를 설정하는 속성이다.

&lt;&lt;&lt;&lt;&lt;&lt;&lt; HEAD \*visible : listbox 컨트롤이 보인다.

## \*hidden : listbox  컨트롤이 보이지 않는다.

### visibility

> > > > > > > 39a9e6e02e8ed3a645ed43cf175046a74b66407c

#### DESCRIPTION

_visible : checkbox 컨트롤이 보인다._ hidden : checkbox 컨트롤이 보이지 않는다.

&lt;&lt;&lt;&lt;&lt;&lt;&lt; HEAD

## {% hint style="info" %} attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 visibility 를 동적으로 제어하기 위해서는 visible property 를 사용해야 한다.

이 속성을 설정하지 않으면 기본으로 visible 로 동작한다.

{% hint style="info" %}
attribute 는 디자인 시점에 설정하는 속성이기 때문에 스크립트로 visibility 를 동적으로 제어하기 위해서는 visible property 를 사용해야 한다.

> > > > > > > 39a9e6e02e8ed3a645ed43cf175046a74b66407c
{% endhint %}

#### VALUES

visible / hidden

#### EXAMPLE

{% code title="\[Static\]" %}
```markup
<<<<<<< HEAD
<select id="optionList" ref="/root/sendData/option" visibility="hidden" overflow="scroll" 
appearance="compact" style="left:190px; top:470px; width:145px; height:60px; font-weight:bold; 
text-align:center; background-color:#ccffff; ">
```
{% endcode %}

> > > > > > > eaecbff44ad16a728baa64cf76485a2e44cd3f57
> > > > > > >
> > > > > > > 39a9e6e02e8ed3a645ed43cf175046a74b66407c

