---
layout: post
title: Unix Find By Date
date: "2011-07-12"
blog: published
categories: 
- unix
- commands
---

<p class="intro"><span class="first-letter">F</span>ind by time is often forgotten by me. Hopefully writing it down will help me remember, because it's very helpful.  I just don't use find enough to remember it.</p>


<code>
find /wherever -name "*whatever*" -mtime -60  # NEWER THAN <br>
find /wherever -name "*whatever*" -mtime +60  # OLDER THAN
</code>

<p>Credit: <a href="http://www.cyberciti.biz/faq/howto-finding-files-by-date/">This is my usual spot.</a></p>
