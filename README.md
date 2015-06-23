## Larger Inbox Compose Window

Because the tiny one sucks and there's no other way to resize it.

Add this to your bookmarks:

    javascript:(function(){var newcss=".k{width:1280px;}.aR{min-height:500px;}";if("\v"=="v"){document.createStyleSheet().cssText=newcss}else{var tag=document.createElement("style");tag.type="text/css";document.getElementsByTagName("head")[0].appendChild(tag);tag[(typeof document.body.style.WebkitAppearance=="string")?"innerText":"innerHTML"]=newcss}})();

<a href="javascript:(function(){var newcss=".k{width:1280px;}.aR{min-height:500px;}";if("\v"=="v"){document.createStyleSheet().cssText=newcss}else{var tag=document.createElement("style");tag.type="text/css";document.getElementsByTagName("head")[0].appendChild(tag);tag[(typeof document.body.style.WebkitAppearance=="string")?"innerText":"innerHTML"]=newcss}})();">test</a>

Click it when the compose window is up.
