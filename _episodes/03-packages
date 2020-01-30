---
title: "Demo 2: Build reproducible packages from notebook and query results"
teaching: 10
exercises: 0
questions:
- "How can we build reproducible packages?"
objectives:
- "Demonstrate the CADRE marketplace."
- "Explain how tools can be built from notebook code"
- "Explain how archives can be created from query results"
- "Explain how to combine tools with archives into reproducible packages"
keypoints:
- "Lessons are stored in Git repositories on GitHub."
- "Lessons are written in Markdown."
- "Jekyll translates the files in the gh-pages branch into HTML for viewing."
- "The site's configuration is stored in _config.yml."
---

This episode describes the tools we use to build and manage lessons.
These simplify many tasks, but make other things more complicated.

## Repositories on GitHub

Our lessons are stored in Git repositories (or "repos") on GitHub.
We use the term *fork* to mean
"a copy of a GitHub-hosted repo that is also hosted on GitHub"
and the term *clone* to mean
"a copy of a GitHub-hosted repo that's located on someone else's machine".
In both cases,
the duplicate has a reference that points to the original repo.

In an ideal world,
we would put all of the common files used by our lessons
(such as the CSS style files and the image files with project logos)
in a template repo.
The master copy of each lesson would be a fork of that repo,
and each author's working copy would be a fork of that master:

![Forking Repositories]({{ page.root }}/fig/forking.svg)

However, GitHub only allows a user to have one fork of any particular repo.
This creates a problem for us because an author may be involved in writing several lessons,
each with its own repo.
We therefore use [GitHub Importer][github-importer] to create new lessons.
After the lesson has been created,
we manually add the [template repository]({{ site.template_repo }}) as a remote called `template`
to update the lesson when the template changes.

![Repository Links]({{ page.root }}/fig/repository-links.svg)


[The next episode]({{ page.root }}/03-organization/) describes these files.

{% include links.md %}
