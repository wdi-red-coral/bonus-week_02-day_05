# CSS Position

![positionIntro](images/positionIntro.png)

![positionIntro2](images/positionIntro2.png)

![positionIntro3](images/positionIntro3.png)

![positionProperties](images/positionProperties.png)

![positionRelative](images/positionRelative.png)

![positionRelativeExample](images/positionRelativeExample.png)

![positionAbsolute](images/positionAbsolute.png)

![positionAbsoluteExample](images/positionAbsoluteExample.png)

![positionFixed](images/positionFixed.png)

![positionFixedExample](images/positionFixedExample.png)


<iframe height="265" style="width: 100%;" scrolling="no" title="Relative positioning" src="//codepen.io/MicFin/embed/ZWzxWx/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/MicFin/pen/ZWzxWx/'>Relative positioning</a> by M
  (<a href='https://codepen.io/MicFin'>@MicFin</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

[codepen_embed height="265" theme_id="0" slug_hash="ZWzxWx" default_tab="html,result" user="MicFin"]See the Pen <a href='https://codepen.io/MicFin/pen/ZWzxWx/'>Relative positioning</a> by M (<a href='https://codepen.io/MicFin'>@MicFin</a>) on <a href='https://codepen.io'>CodePen</a>.[/codepen_embed]

<div class="codepen" data-height="265" data-theme-id="0" data-default-tab="html,result" data-user="MicFin" data-slug-hash="ZWzxWx" data-prefill='{"title":"Relative positioning","description":"\n\nForked from [Lisa Plesko](http://codepen.io/lisaplesko/)&apos;s Pen [Relative positioning](http://codepen.io/lisaplesko/pen/Kweejo/).","tags":[],"stylesheets":[],"scripts":[]}'>
  <pre data-lang="html">&lt;h2>Relative positioning: "I'm relative to myself"&lt;/h2>
&lt;p> Although I've come outside of the page flow, everyone else respects where I used to be.&lt;/p>

&lt;div class="box">&lt;/div>
&lt;div class="box">&lt;/div>
&lt;div class="box">&lt;/div>
&lt;div class="box clear">&lt;/div>
&lt;div class="box relative">&lt;/div>
&lt;div class="box">&lt;/div>
&lt;div class="box clear">&lt;/div>
&lt;div class="box">&lt;/div>
&lt;div class="box">&lt;/div></pre>
  <pre data-lang="css" >.box.relative {
  position: relative;
  background-color: crimson;
  bottom: 10px;
  right: 10px;
}













.box {
  float: left;
  width: 50px;
  height: 50px;
  margin: 2px;
  background-color: steelblue;
}

.clear { /* I'm just creating a break in floats to make an equal grid */
  clear: both;
  content: " "
}

body {
  font-family: tahoma;
}</pre>
  
</div>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>