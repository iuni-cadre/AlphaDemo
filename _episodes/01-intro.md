---
title: "Overview of the CADRE project (Pentchev)"
time: 10
questions:
- "What is CADRE"
objectives:
- "Introduce the CADRE project and announce the Alpha release"
keypoints:
- "CADRE, or the shared big data gateway"
- "The Alpha Demos"
---

![Source and Destination Files]({{ page.root }}/fig/file-mapping.svg)

> ## Collections
>
> As described [earlier]({{ page.root }}/02-tooling/#collections),
> files that appear as top-level items in the navigation menu are stored in the root directory.
> Files that appear under the "extras" menu are stored in the `_extras` directory,
> while lesson episodes are stored in the `_episodes` directory.
{: .callout}

# Standard Files

When the lesson repository is first created,
the initial author should create a `README.md` file containing
a one-line explanation of the lesson's purpose.

The [lesson template]({{ site.template_repo }}) provides the following files
which should *not* be modified:

*   `CONDUCT.md`: the code of conduct.
*   `LICENSE.md`: the lesson license.
*   `Makefile`: commands for previewing the site, cleaning up junk, etc.

## Starter Files

The `bin/lesson_initialize.py` script creates files that need to be customized for each lesson:

`CONTRIBUTING.md`
:   Contribution guidelines.
    The `issues` and `repo` links at the bottom of the file must be changed
    to match the URLs of the lesson:
    look for uses of `FIXME`.

`_config.yml`
:   The [Jekyll][jekyll] configuration file.
    This must be edited so that its links and other settings are correct for this lesson.
    *   `carpentry` should be either "dc" (for Data Carpentry), "lc" (for Library Carpentry), or "swc" (for Software Carpentry).
    *   `title` is the title of your lesson,
        e.g.,
        "Defence Against the Dark Arts".
    *   `email` is the contact email address for the lesson.
    
## Figures

All figures related with the lesson **must** be placed inside the directory `fig` at the root of the project.

{% include links.md %}
