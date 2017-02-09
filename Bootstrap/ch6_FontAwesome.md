Font Awesome is a icon library. Icons are treated like fonts.

To add them to your file:
```html
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css"/>
```

`<i>` element is used for icon. You can use different icons by specifying corresponding classes, e.g. `fa-info-circle`, `fa-trash`, `fa-thumbs-up`

For more information [check their webpage.](http://fontawesome.io/icons/)

```html
<i class="fa fa-info-circle"></i>
```
You can add icons to other elements, e.g. buttons:

```html
<button class="btn btn-block btn-primary">Like
   <i class="fa fa-thumbs-up"></i>
</button>
```