# minusbutton
‣example

----index.html----
````
<div id="AppMinus">
      <mycomp
      :width = 500
      :height = 300
      @minusclick="minus"></mycomp> //@minusclick: ボタンが押されたら発火
</div>
  ````
  
  ----index.js----
  ````
import Vue from 'vue';
import AppMinus from 'minusbutton';

new Vue({
    el: '#AppMinus',
    components: {
        'mycomp': AppMinus
    },
    methods: {
        Minus(){
            console.log("minus")
        }
    }
})
````
