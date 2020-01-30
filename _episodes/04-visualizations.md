---
title: "Demo 3: Visualizations and word clouds (Silva)"
teaching: 20
exercises: 0
questions:
- "How can we perform data visualization and use reproducible tools for my own data"
objectives:
- "Demonstrate word cloud visualizations."
- "Demonstrate network visualizations."
- "Explain how we can build reproducible tools."
- "Explain how you can combine existing tools with your own data to create reproducible packages"
keypoints:
- "Lesson episodes are stored in _episodes/dd-subject.md."
- "Each episode's title must include a title, time estimates, motivating questions, lesson objectives, and key points."
---

## Formatting Code

Inline code fragments are formatted using back-quotes.
Longer code blocks are formatted by opening and closing the block with `~~~` (three tildes),
with a class specifier after the block:

{% raw %}
    ~~~
    for thing in collection:
        do_something
    ~~~
    {: .source}
{% endraw %}

which is rendered as:

~~~
for thing in collection:
    do_something
~~~
{: .source}

The class specified at the bottom using an opening curly brace and colon,
the class identifier with a leading dot,
and a closing curly brace.
The [template]({{ site.template_repo }}) provides three styles for code blocks:

~~~
.source: program source.
~~~
{: .source}

~~~
.output: program output.
~~~
{: .output}

~~~
.error: error messages.
~~~
{: .error}

{% include links.md %}
