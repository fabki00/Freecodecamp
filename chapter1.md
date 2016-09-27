# jQuery

$ - access elements of html document

 ```$(document).ready(function() {
});```
The above jQuery statement should be placed between ```<script></script>``` tags in HTML document.
You can also access individual elements in the HTML documents using the $ symbol:

* 
```$("button").addClass("animated")```  - will add class *animated* to all elements of type button.
* 
```$(".well").addClass("animated shake")``` will add class *animated* and *shake* to elements of class ```well```. 
* 
```$("#target1").removeClass("animated")``` will remove class *animated* from element with id ```target1```.