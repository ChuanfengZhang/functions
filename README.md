#How to use
--
For *EventUtil.js*  
```  
var btn = document.getElementById("myBtn");
var handler = function(){
	alert("Clicked");
};  
**EventUtil.addHandler(btn,"click",handler);**  
**EventUtil.removeHandler(btn,"click",handler);**  
```
--  
for *addLoadEvent.js*  
**addLoadEvent(yourfunction);**
--
for *insertAfter.js*  
**insertAfter(newElement,targetElement);**