# slider-drag
 
 - 原生`js`实现的仿ele滚动插件
 
```html
    <div class="box">
        <div class="box-nav">
            <div class="hover">0</div>
            <div class=""><a href="#4">1</a></div>
            <div class="">2</div>
            <div class="">3</div>
            <div class="">4</div>
            <div class="">5</div>
            <div class="">6</div>
            <div class="">7</div>
            <div class="">1</div>
            <div class="">1</div>
        </div>
        <div class="box-center">
            <div>0</div>
            <div>1</div>
            <div>2</div>
            <div>3</div>
            <div>4</div>
            <div>5</div>
            <div>6</div>
            <div>7</div>
            <div>8</div>
        </div>
    </div>
```
```javascript
    scroll.newClass({
            box: document.querySelector('.box'),
            boxNav: document.querySelector('.box-nav'),
            boxNavDiv: document.querySelector('.box-nav').getElementsByTagName('div'),
            boxCenter: document.querySelector('.box-center'),
            boxCenterDiv: document.querySelector('.box-center').getElementsByTagName('div'),
            item: 0
        })
```
