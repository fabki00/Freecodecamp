To make image responisve give its element class `img-responsive`


```
 <img class="img-responsive" src="https://bit.ly/fcc-running-cats"></img>
```

You can evenly space any elements by nesting them within their own `<div>` elements with appropriate class, e.g. `col-xs-6`. For example evenly space radio buttons in a form:

```html
         <label><input type="radio" name="indoor-outdoor"> Indoor</label>
      </div>
      <div class="col-xs-6">
        <label><input type="radio" name="indoor-outdoor"> Outdoor</label>
      </div>
    </div>
    <label><input type="checkbox" name="personality"> Loving</label>
    <label><input type="checkbox" name="personality"> Lazy</label>
```