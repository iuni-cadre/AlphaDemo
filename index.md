---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---

{% include gh_variables.html %}

test

> ## Prerequisites
>
> test2
{: .prereq}

> ## Ten Things You Need To Know
>
> 0.  Don't panic.
> 1.  Create a new lesson by using GitHub Import, *not* by forking.
> 2.  Run `bin/lesson_initialize.py` *once* in a new lesson repository to set up standard files.
> 3.  Run `make lesson-check` to check that the lesson is formatted correctly.
> 4.  Put lesson episodes in `_episodes` (or `_episodes_rmd` if you are writing in RMarkdown).
> 5.  Run `make serve` to preview the lesson website locally.
> 6.  Do *not* commit the generated HTML files in the `_site` directory.
> 7.  Style blocks and code samples by putting `{: .stylename}` on a newline *after* the block or code.
> 8.  Put solutions inside challenges using nested blockquotes.
> 9.  File issues and template fixes in the [styles repository][styles],
>     and enhancements to this documentation in this one.
{: .checklist}

{% include links.md %}
