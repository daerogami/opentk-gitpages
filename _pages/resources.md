---
layout: page
title: Resources
permalink: /resources/
menuItem: true
---

<!-- Content -->
{% assign guides = site.pages | sort: "level" %}

<div class="col-lg-4 col-sm-12">
	<a class="h2" href="https://daerogami.gitbooks.io/opentk-manual/" target="_blank">Manual on GitBooks</h2>
</div>

<div class="col-lg-4 col-sm-12">
	<h2>Other Helpful Links</h2>
	<ul>
		<li>
			<a href="{{ "/projects/" | prepend: site.baseurl }}">
				Projects using OpenTK
			</a>
		</li>
		<li>
			<span style="color:red">OpenTK Examples</span>
		</li>
	</ul>
	<h2>External Links</h2>
	<ul>
		<li>
			<a href="https://learnopengl.com/">Learn OpenGL</a>
		</li>
	</ul>
</div>