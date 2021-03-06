---
title: SecoFire Style Guidelines
---
<html>
  {% include head.html %}
  <body>
	{% include header.html %}
	<div id="main_content_wrap" class="outer">
		<section id="main_content" class="inner">
			<h3>
				<a id="welcome-to-github-pages" class="anchor" href="#welcome-to-github-pages" aria-hidden="true">
					<span aria-hidden="true" class="octicon octicon-link"></span>
				</a>
				SecoFire Layout.
			</h3>
			<p>Element tag <code>body</code> should use <code>layout="column"</code> attribure in addition with <code>flex</code> attribute. To learn more in details how this works please check following: <button type="button" class="btn btn-default" target="_blank" onclick="window.location.href='https://material.angularjs.org/latest/layout/container'">angular material - layout containers</button></p>
			<p>Please note that first child element of body tag is <code>div</code> element with <code>id="chrome_ctrl_placeholder"</code>. It is important to place this element here as it is a placeholder for SharePoint Chrome Control. Ommiting this element would disable user to easily return to SharePoint site.</p>
			{% include layout_1.html %}

			<p>Donec eget dolor ut turpis rhoncus tincidunt dignissim ut elit. Nam est sapien, pharetra eget nunc ac, euismod congue magna.</p>
			<h3>
				<a id="designer-templates" class="anchor" href="#designer-templates" aria-hidden="true">
					<span aria-hidden="true" class="octicon octicon-link"></span>
				</a>
				Designer Templates
			</h3>
			
			<p>We’ve crafted some handsome templates for you to use. Go ahead and click 'Continue to layouts' to browse through them. You can easily go back to edit your page before publishing. After publishing your page, you can revisit the page generator and switch to another theme. Your Page content will be preserved.</p>

			<h3>
				<a id="creating-pages-manually" class="anchor" href="#creating-pages-manually" aria-hidden="true">
					<span aria-hidden="true" class="octicon octicon-link"></span>
				</a>
				Creating pages manually
			</h3>

			<p>If you prefer to not use the automatic generator, push a branch named <code>gh-pages</code> to your repository to create a page manually. In addition to supporting regular HTML content, GitHub Pages support Jekyll, a simple, blog aware static site generator. Jekyll makes it easy to create site-wide headers and footers without having to copy them across every page. It also offers intelligent blog support and other advanced templating features.</p>

			<h3>
				<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true">
					<span aria-hidden="true" class="octicon octicon-link"></span>
				</a>
				Authors and Contributors
			</h3>

			<p>You can @mention a GitHub username to generate a link to their profile. The resulting <code>&lt;a&gt;</code> element will link to the contributor’s GitHub Profile. For example: In 2007, Chris Wanstrath (<a href="https://github.com/defunkt" class="user-mention">@defunkt</a>), PJ Hyett (<a href="https://github.com/pjhyett" class="user-mention">@pjhyett</a>), and Tom Preston-Werner (<a href="https://github.com/mojombo" class="user-mention">@mojombo</a>) founded GitHub.</p>

			<h3>
				<a id="support-or-contact" class="anchor" href="#support-or-contact" aria-hidden="true">
					<span aria-hidden="true" class="octicon octicon-link"></span>
				</a>
				Support or Contact
			</h3>

			<p>Having trouble with Pages? Check out our <a href="https://help.github.com/pages">documentation</a> or <a href="https://github.com/contact">contact support</a> and we’ll help you sort it out.</p>
		</section>
	</div>
	{% include footer.html %}
	{% include scripts.html %}
	</body>
</html>
