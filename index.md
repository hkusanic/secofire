---
title: SecoFire Style Guidelines
---
<!DOCTYPE html>
<html>
  <head>
	<meta charset='utf-8'>
	<meta http-equiv="X-UA-Compatible" content="chrome=1">
	<meta name="description" content="Secofire : ">

	<link rel="stylesheet" type="text/css" media="screen" href="stylesheets/stylesheet.css">
	<link rel="stylesheet" type="text/css" media="screen" href="css/syntax.css">
	<title>Seco Fire Style Guidelines</title>
  </head>

  <body>

	<!-- HEADER -->
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

	

  </body>
</html>
