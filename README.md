# polymer-gridstack
An extension of gridstack library to support drag n drop and resize functioanlity for polymer elements.

Originally inspired by https://github.com/troolee/gridstack.js

You can get component from bower as:

`bower install polymer-gridstack --save`

Usage 
``` html
          <polymer-gridstack id="grid1">
          <div class="grid-stack" data-gs-width="12">
              <div class="grid-stack-item" data-gs-x="0" data-gs-y="0" data-gs-width="4" data-gs-height="2">
                    <div class="grid-stack-item-content">DIV ONE</div>
                </div>
                <div class="grid-stack-item" data-gs-x="4" data-gs-y="0" data-gs-width="4" data-gs-height="4">
                    <div class="grid-stack-item-content">DIV TWO</div>
                </div>
                <div class="grid-stack-item" data-gs-x="8" data-gs-y="0" data-gs-width="2" data-gs-height="2" data-gs-min-width="2" data-gs-no-resize="yes">
                    <div class="grid-stack-item-content"> DIV THREE NO RESIZE </div>
                </div>
                <div class="grid-stack-item" data-gs-x="10" data-gs-y="0" data-gs-width="2" data-gs-height="2">
                    <div class="grid-stack-item-content"> DIV FOUR</div>
                </div>
                <div class="grid-stack-item" data-gs-x="0" data-gs-y="4" data-gs-width="2" data-gs-height="2">
                    <div class="grid-stack-item-content">DIV FIVE</div>
                </div>
                <div class="grid-stack-item" data-gs-x="2" data-gs-y="4" data-gs-width="2" data-gs-height="4">
                    <div class="grid-stack-item-content">DIV SIX</div>
                </div>
                <div class="grid-stack-item" data-gs-x="8" data-gs-y="4" data-gs-width="4" data-gs-height="2">
                    <div class="grid-stack-item-content">DIV SEVEN</div>
                </div>
                <div class="grid-stack-item" data-gs-x="0" data-gs-y="6" data-gs-width="2" data-gs-height="2">
                    <div class="grid-stack-item-content">DIV EIGHT</div>
                </div>
                <div class="grid-stack-item" data-gs-x="4" data-gs-y="6" data-gs-width="4" data-gs-height="2">
                    <div class="grid-stack-item-content">DIV NINE</div>
                </div>
                <div class="grid-stack-item" data-gs-x="8" data-gs-y="6" data-gs-width="2" data-gs-height="2">
                    <div class="grid-stack-item-content">DIV TEN</div>
                </div>
                <div class="grid-stack-item" data-gs-x="10" data-gs-y="6" data-gs-width="2" data-gs-height="2">
                    <div class="grid-stack-item-content">DIV ELEVEN</div>
                </div>
            </div>            
          </polymer-gridstack>
```

``` js
document.getElementById("grid1").dataProperties = {
    width: 12
}
```
For a list of options see : https://github.com/troolee/gridstack.js/tree/develop/doc#options and for a live demo visit http://www.vinodlouis.com/demos/polymer-gridstack-demo/

