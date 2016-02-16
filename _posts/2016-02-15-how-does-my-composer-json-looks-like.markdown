---
layout:     post
title:      "My composer.json"
subtitle:   "How Does My composer.json file looks like"
date:       2016-02-15 12:00:00
author:     "Raffi Hovhannesian"
header-bg: "#b81d18"
---
For small to medium sized projects I end up using the following in almost every project.
<h2>Dependencies</h2>
<ul>
<li>PHP 5.3.0 and above v7 is coming soon.</li>
<li>Monolog: comes required by Slim Skeleton and is a very useful tool. https://github.com/slimphp/Slim-Skeleton</li>
<li>Slim Framework.</li>
<li>Twig templating system.</li>
<li>Illuminate: a full database toolkit for PHP. https://github.com/illuminate/database</li>
<li>Kint: an amazing tool for debugging.</li>
<li>Kint: an amazing tool for debugging.</li>
</ul>
<h2>The composer.json File</h2>
<pre>
{
    "name": "My Awesome Project",
    "description": "No Description",
    "authors": [
        {
            "name": "Raffi Hovahnnesian",
            "email": "name@example.com",
            "homepage": ""
        }
    ],
    "require": {
        "php": ">=5.3.0",
        "monolog/monolog": "1.*",
        "slim/slim": "2.*",
        "slim/views": "0.*",
        "twig/twig": "1.*",
        "illuminate/database": "*",
        "raveren/kint": "^1.0",
    }
}
</pre>
