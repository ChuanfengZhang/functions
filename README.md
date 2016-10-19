#How to use
For *EventUtil.js*  
```  
var btn = document.getElementById("myBtn");
var handler = function(){
	alert("Clicked");
};  
```
**EventUtil.addHandler(btn,"click",handler);**  
**EventUtil.removeHandler(btn,"click",handler);**  

--  
For *addLoadEvent.js*  
**addLoadEvent(yourfunction);**

--
For *insertAfter.js*  
**insertAfter(newElement,targetElement);**