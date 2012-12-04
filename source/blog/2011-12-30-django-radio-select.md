---
layout: post
title: Django RadioSelect Patching
blog: published
categories: 
- web
- django
date: "2011-12-30"
---

<p class="intro"><span class="first-letter">I</span> had to change up the standard Django RadioSelect form widget today because I didn't want the label tags wrapping the input like it usually does.  This is normally okay (and semantically fine), but the label wrap can be difficult to style when using it in a list.  It was a bit confusing at first but generally simple once I figured it all out.</p>

A couple good links that helped were here:

<ul>
<li>
<a href="
http://stackoverflow.com/questions/5558509/django-rendering-radio-button-options-with-extra-information-from-model">Stack Overflow - Rendering Radio with Options</a>
</li>
<li>
<a href="https://code.djangoproject.com/attachment/ticket/4228/radioselect_renderer.patch">Django Patch with example</a>
</li>
</ul>

Here's a <a href="https://gist.github.com/1538180">gist</a> with what I did.

I am just getting the hang of Django widgets, so if there is a better way of doing this then let me know!
