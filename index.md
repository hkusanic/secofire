---
title: SecoFire Style Guidelines
---
<html>
  <head>
	<meta charset='utf-8'>
	<meta http-equiv="X-UA-Compatible" content="chrome=1">
	<meta name="description" content="Secofire : ">
	<!-- Latest compiled and minified CSS -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
	<link rel="stylesheet" type="text/css" media="screen" href="stylesheets/stylesheet.css">
	<link rel="stylesheet" type="text/css" media="screen" href="css/syntax.css">
	<link rel="stylesheet" type="text/css" media="screen" href="css/pygments/github-light.css">
	<title>Seco Fire Style Guidelines</title>
  </head>
  <body>
	<nav class="navbar navbar-default navbar-static-top">
		<div class="container-fluid">
			<!-- Brand and toggle get grouped for better mobile display -->
			<div class="navbar-header">
				<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
					<span class="sr-only">Toggle navigation</span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
				</button>
				<a class="navbar-brand" href="#">SecoFire</a>
			</div>

			<!-- Collect the nav links, forms, and other content for toggling -->
			<div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
				<ul class="nav navbar-nav">
					<li class="active"><a href="#">Home <span class="sr-only">(current)</span></a></li>
					<li><a href="#">Link</a></li>
					<li class="dropdown">
						<a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
						<ul class="dropdown-menu">
							<li><a href="#">Action</a></li>
							<li><a href="#">Another action</a></li>
							<li><a href="#">Something else here</a></li>
							<li role="separator" class="divider"></li>
							<li><a href="#">Separated link</a></li>
							<li role="separator" class="divider"></li>
							<li><a href="#">One more separated link</a></li>
						</ul>
					</li>
				</ul>
				<form class="navbar-form navbar-left">
					<div class="form-group">
						<input type="text" class="form-control" placeholder="Search">
					</div>
					<button type="submit" class="btn btn-default">Submit</button>
				</form>
				<ul class="nav navbar-nav navbar-right">
					<li><a href="#">Link</a></li>
					<li class="dropdown">
						<a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
						<ul class="dropdown-menu">
							<li><a href="#">Action</a></li>
							<li><a href="#">Another action</a></li>
							<li><a href="#">Something else here</a></li>
							<li role="separator" class="divider"></li>
							<li><a href="#">Separated link</a></li>
						</ul>
					</li>
				</ul>
			</div><!-- /.navbar-collapse -->
		</div><!-- /.container-fluid -->
	</nav>
	<div id="header_wrap" class="outer">
		<header class="inner">
		  <a id="forkme_banner" href="https://github.com/hkusanic/secofire">View on GitHub</a>

		  <h1 id="project_title">Secofire Style Guidelines</h1>
		  <h2 id="project_tagline"></h2>

			<section id="downloads">
			  <a class="zip_download_link" href="https://github.com/hkusanic/secofire/zipball/master">Download this project as a .zip file</a>
			  <a class="tar_download_link" href="https://github.com/hkusanic/secofire/tarball/master">Download this project as a tar.gz file</a>
			</section>
		</header>
	</div>

	<!-- MAIN CONTENT -->
	<div id="main_content_wrap" class="outer">
	  <section id="main_content" class="inner">
		<h3>
<a id="welcome-to-github-pages" class="anchor" href="#welcome-to-github-pages" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Welcome to Seco Fire Style Guidelines.</h3>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus molestie libero vel orci volutpat, ut maximus velit placerat. In at condimentum lectus. Maecenas fringilla varius ligula vel imperdiet. Etiam eget lobortis lectus. Morbi imperdiet turpis massa, in dapibus arcu sodales eu. Donec vitae ligula id libero placerat gravida et lobortis eros. Suspendisse dictum blandit libero quis sodales.<a href="https://guides.github.com/features/mastering-markdown/">Link example 1</a>, Aliquam lobortis tellus sit amet ante euismod, et semper nisi ultricies. Nullam convallis diam ante, non euismod justo aliquam eget. Vestibulum sit amet sagittis tellus. Vestibulum at aliquet risus.

<code>
{% highlight html %}
  <!DOCTYPE html>
  <html
	lang="en"
	ng-app="seco.fire.web" ng-strict-di>
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
{% endhighlight %}
</code>

<code>
{% highlight html %}
  <!DOCTYPE html>
  <html
	lang="en"
	ng-app="seco.fire.web" ng-strict-di>
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
{% endhighlight %}
</code>


Donec eget dolor ut turpis rhoncus tincidunt dignissim ut elit. Nam est sapien, pharetra eget nunc ac, euismod congue magna.</p>
<h3>
<a id="designer-templates" class="anchor" href="#designer-templates" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Designer Templates</h3>

<p>We’ve crafted some handsome templates for you to use. Go ahead and click 'Continue to layouts' to browse through them. You can easily go back to edit your page before publishing. After publishing your page, you can revisit the page generator and switch to another theme. Your Page content will be preserved.</p>

<h3>
<a id="creating-pages-manually" class="anchor" href="#creating-pages-manually" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Creating pages manually</h3>

<p>If you prefer to not use the automatic generator, push a branch named <code>gh-pages</code> to your repository to create a page manually. In addition to supporting regular HTML content, GitHub Pages support Jekyll, a simple, blog aware static site generator. Jekyll makes it easy to create site-wide headers and footers without having to copy them across every page. It also offers intelligent blog support and other advanced templating features.</p>

<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Authors and Contributors</h3>

<p>You can @mention a GitHub username to generate a link to their profile. The resulting <code>&lt;a&gt;</code> element will link to the contributor’s GitHub Profile. For example: In 2007, Chris Wanstrath (<a href="https://github.com/defunkt" class="user-mention">@defunkt</a>), PJ Hyett (<a href="https://github.com/pjhyett" class="user-mention">@pjhyett</a>), and Tom Preston-Werner (<a href="https://github.com/mojombo" class="user-mention">@mojombo</a>) founded GitHub.</p>

<h3>
<a id="support-or-contact" class="anchor" href="#support-or-contact" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Support or Contact</h3>

<p>Having trouble with Pages? Check out our <a href="https://help.github.com/pages">documentation</a> or <a href="https://github.com/contact">contact support</a> and we’ll help you sort it out.</p>
	  </section>
	</div>

	<!-- FOOTER  -->
	<div id="footer_wrap" class="outer">
	  <footer class="inner">
		<p class="copyright">Seco Fire style guides are maintained by <a href="https://github.com/hkusanic">Hrvoje Kusanic</a></p>
		<!--<p>Published with <a href="https://pages.github.com">GitHub Pages</a></p>-->
	  </footer>
	</div>

	<script src="https://code.jquery.com/jquery-3.1.1.slim.min.js" integrity="sha256-/SIrNqv8h6QGKDuNoLGA4iret+kyesCkHGzVUUV0shc=" crossorigin="anonymous"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
  </body>
</html>
