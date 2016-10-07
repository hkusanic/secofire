---
title: This will be used as the title-tag of the page head
---

# This is a H1

[the clickable text](http://xlson.com/)

* Bullet lists are also easy to create
* One more

Example of code block
```html
<!DOCTYPE html>
<html lang="en" ng-app="seco.fire.web" ng-strict-di>
	<head>
		<meta http-equiv="X-UA-Compatible" content="IE=Edge" />
		<meta charset="UTF-8">
		<meta name="viewport" content="initial-scale=1, maximum-scale=1, user-scalable=no" />
		<title>The App</title>
		<script src="https://ajax.aspnetcdn.com/ajax/4.0/1/MicrosoftAjax.js" type="text/javascript"></script>
		<script src="lib/system.js"></script>
		<script src="config.js"></script>
		<script>
		System.import('app/app');
		</script>
	</head>
	<body layout="column" flex>
		<div id="chrome_ctrl_placeholder"></div>
		<seco-fire-app layout="column" flex>
		Loading
		<md-button class="md-raised md-primary">Primary</md-button>
		<md-progress-circular class="md-warn md-hue-3" md-mode="indeterminate" md-diameter="70"></md-progress-circular>
		</seco-fire-app>
		<!-- we need a form tag on the page, so that ASP.NET functionalities like ScriptManager work -->
		<form id="form1" runat="server"></form>
	</body>
</html>
```