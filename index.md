---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---

<h2 id="lesson_intro">Lesson description</h2>

{% comment %}
This is an INTRODUCTION to the LESSON and why the people should care about this workshop. Write a good pitch in the file that is being reference to (found in _includes/data_reuse/intro_lesson.html)
{% endcomment %}

{% include data_reuse/intro_lesson.html %}


{% comment %} 
{% include gh_variables.html %}

For guidelines on how to develop curriculum content, please visit
[The Carpentries Curriculum Development Handbook][curriculum-handbook].

This lesson shows how to use [The Carpentries]({{ site.carpentries_site}})
lesson template. The materials below assume familiarity with tools such as GitHub, Markdown,
and Jekyll. For more guidance, please visit the [Technological introductions][tech-intro]
section of The Carpentries Curriculum Development Handbook.

For guidelines on how to help improve our lessons and this template,
please see [the contribution guidelines][contributing];
for guidelines on how to set up your machine to preview changes locally,
please see [the setup instructions]({{ page.root }}{% link setup.md %}).


> ## Prerequisites
>
> Use the `.prereq` style to specify prerequisites.
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
> 7.  Style blocks and code samples by putting `{: .stylename}` on a newline *after* the block or
      code.
> 8.  Put solutions inside challenges using nested blockquotes.
> 9.  File issues and template fixes in the [styles repository][styles],
>     and enhancements to this documentation in this one.
{: .checklist}

[curriculum-handbook]: https://carpentries.github.io/curriculum-development/
[tech-intro]: https://carpentries.github.io/curriculum-development/technological-introductions.html

{% include links.md %}

{% endcomment %}




