---
layout: post
title:  "A Test Post"
date:   2023-03-09 17:45:47 -0500
categories: jekyll blog-test
#excerpt_separator: "<!--more-->"
published: false
---
This is a test blog post that I am using to see what different text elements look like with the current Jekyll theme.

Here's a second paragraph.

<!-- more -->

<hr>
## Testing Syntax

I am using kramdown-flavorerd markdown. Full syntax guide [here](https://kramdown.gettalong.org/syntax.html).

Here is some R code:
{% highlight r%}
df <- data.frame(var_1 = rnorm(),
                 var_2 = rnorm() + 1)

head(df)
{% endhighlight %}

Code can also be displayed by using three `~~~` as a delimiter. Follow the closing delimiter with `{: .language-LANG}`, replacing LANG with the programming language used.

~~~
df <- data.frame(var_1 = rnorm(),
                 var_2 = rnorm() + 1)

head(df)
~~~
{: .language-r}

It looks like I can include links either in standard markdown link format (`[text](URL)`), or
as a defined link (`[text][label]`, followed by `[label]: URL`). 

# Heading 1

Heading 1 with `=`
==================

## Heading 2

Heading 2 with `-`
------------------

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

> Blockquoted text. A communi observantia non est recedendum. Vivamus sagittis lacus vel augue laoreet rutrum faucibus. Nihilne te nocturnum praesidium Palati, nihil urbis vigiliae.
> > A nested blockquote
>
> ## Header in a blockquote
>
> * List item in a blockquote

<hr>
`<hr>` prints a horizontal rule.
<hr>

# Header with id {#header-with-id}