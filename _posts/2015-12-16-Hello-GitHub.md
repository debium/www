---
layout: post
permalink: /HelloGitHub.html
---

<!-- BrowserCheck credit Michael Bleidistel !-->
<div id="browser">
# Hello GitHub!
This is a place to share ideas about anything! Need help on an Internet based project? Want to make a Minecraft mod? Design a cryptocurrency? Do them all in one? You've came to the right place, kind sir or lady. This is a place for free technological, creative, and logical thinking. Feel welcome on my site, send me a pull request, and I'll gladly consider your ideas! Every creative thinker is welcome here, 
</div>

<script>
	function BrowserCheck() //Returns an array of [name,number]
		var N= navigator.appName, ua= navigator.userAgent, tem;
		var M= ua.match(/(opera|chrome|safari|firefox|msie|trident)\/?\s*(\.?\d+(\.\d+)*)/i);
		if(M && (tem= ua.match(/version\/([\.\d]+)/i))!= null) {M[2]=tem[1];}
		M= M? [M[1], M[2]]: [N, navigator.appVersion,'-?'];
		return M;
	}
	document.getElementById("browser").innerHTML += (" even users of "+BrowserCheck()[0]+" "+BrowserCheck()[1]+"!"); //returns name and number
</script>
