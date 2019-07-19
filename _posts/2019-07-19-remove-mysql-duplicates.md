---
ID: 1145
post_title: Remove MySQL Duplicates
author: praison
post_excerpt: ""
layout: post
permalink: >
  https://praison.com/2019/07/remove-mysql-duplicates/
published: true
post_date: 2019-07-19 22:33:58
---
<!-- wp:code -->
<pre class="wp-block-code"><code>ALTER IGNORE TABLE `table_name` ADD UNIQUE (title, SID)</code></pre>
<!-- /wp:code -->