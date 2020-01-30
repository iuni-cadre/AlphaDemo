---
title: CADRE Alpha Demo (Version alpha 1.0 02-10-2020)
---

> ## Collections
>
> As described [earlier]({{ page.root }}/02-tooling/#collections),
> files that appear as top-level items in the navigation menu are stored in the root directory.
> Files that appear under the "extras" menu are stored in the `_extras` directory,
> while lesson episodes are stored in the `_episodes` directory.
{: .callout}

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

## Requirements

* A GitHub account
* A working [Python 3.4+](https://www.python.org) environment to run the lesson initialization
  script
* (Optional) A local install of [Jekyll](https://jekyllrb.com/) (version 3.2 or higher) which will
  require the Ruby language to be installed.

## Creating a New Lesson

4.  **R Packages**.
    We use [knitr][cran-knitr], [stringr][cran-stringr], and [checkpoint][cran-checkpoint]
    to format lessons written in R Markdown,
    so you will need to install these to build R lessons
    (and this example lesson). The best way to install these packages is to open an R terminal and type:

    ~~~
    install.packages(c('knitr', 'stringr', 'checkpoint', 'ggplot2'),
                     repos = 'https://cran.rstudio.com', dependencies = TRUE)
    ~~~
    {: .language-r}

If you want to run `bin/lesson_check.py` (which is invoked by `make lesson-check`)
you will need Jekyll (so that you have its Markdown parser, which is called Kramdown)
and the [PyYAML][pyyaml] module for Python 3.

![Source and Destination Files]({{ page.root }}/fig/file-mapping.svg)

{% include links.md %}
