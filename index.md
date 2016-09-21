---
layout: home
title: Home
landing-title: Hi, my name is Forty
description: This is the Jekyll Version of the Forty Theme by HTML5 UP.<br>You can edit this content in the `description` front matter<br>field of your index.md file.
image: assets/images/banner.jpg
author:
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
	<span class="image">
		<img src="{{ site.baseurl }}/{{ page.image }}" alt="" />
	</span>
		<header class="major">
			<h1>{{ page.landing-title }}</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ page.description }}</p>
			<ul class="actions">
				<li><a href="#one" class="button next scrolly">Get Started</a></li>
			</ul>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- One -->
{% include tiles.html %}

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>Sample Product Page</h2>
		</header>
		<p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus pharetra. Pellentesque condimentum sem. In efficitur ligula tate urna. Maecenas laoreet massa vel lacinia pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus amet pharetra et feugiat tempus.</p>
		<ul class="actions">
			<li><a href="products/sample-product" class="button next">Get Started</a></li>
		</ul>
	</div>
</section>

</div>
