<html>
<head>
	<meta charset="utf-8">
	<title>Oh God, I think I'm geerrrna BLLLLLOOOGG!</title>
</head>
<body>
	Testing GH Pages

	<ul>
	{% for post in site.posts %}
		<li>
		  <a href="{{ post.url }}">{{ post.title }}</a>
		</li>
	{% endfor %}
</ul>
</body>
</html>
