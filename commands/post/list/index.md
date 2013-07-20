---
layout: default
title: 'wp post list'
---

`wp post list` - Get a list of posts.

### OPTIONS

	--<field>=<value>
			One or more args to pass to WP_Query.

	--fields=<fields>
			Limit the output to specific object fields. Defaults to ID,post_title,post_name,post_date,post_status.

	--format=<format>
			Output list as table, CSV, JSON, or simply IDs. Defaults to table.

### EXAMPLES

	wp post list --format=ids

	wp post list --post_type=post --posts_per_page=5 --format=json

	wp post list --post_type=page --fields=post_title,post_status

