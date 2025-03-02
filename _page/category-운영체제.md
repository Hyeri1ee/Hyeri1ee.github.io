---
title: "운영체제"
layout: archive
permalink: /operating_system
author_profile: true
sidebar:
    nav: "sidebar-category"
---
{`% assign posts = site.categories.human %`}
{`% for post in posts %`}` `{`% include archive-single.html type=page.entries_layout %`}` `{`% endfor %`}
