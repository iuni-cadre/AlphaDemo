---
title: "Demo02: Networks and visualizations (Silva)"
teaching: 25
exercises: 0
questions:
- "How can we build networks from query results and visualize them"
objectives:
- "Demonstrate word cloud visualizations."
- "Demonstrate network visualizations."
- "Explain how you can reproduce the result using public packages"
- "Demonstrate advanced intreactive visualizations"
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
