---
layout: post
title: ARIA Tags - Accessibility Code Snippets
description: Resource post for my team at the Accessibility hackathon, 18th and 19th March
image: "/images/posts/TV-1.jpg"
---

The majority of this content and code were taken from the [WebAim] and [WCAG 2.0] websites.

## Skip links

A screen reader will always try to read aloud any navigation it comes across, on every page load, no matter what. This can become annoying to those users. Providing a mechanism with which to quickly bypass it can greatly improve their experience. With as little as two keystrokes, they can jump right to the relevant content.

#### CSS
{% highlight css %}
.skip {
    position: absolute;
    top: -1000px;
    left: -1000px;
    height: 1px;
    width: 1px;
    text-align: left;
    overflow: hidden;
}

a.skip:active, 
a.skip:focus, 
a.skip:hover {
    left: 0; 
    top: 0;
    width: auto; 
    height: auto; 
    overflow: visible; 
}
{% endhighlight %}

#### HTML

{% highlight html %}
<body>
<a href="#maincontent">Skip to main content</a> 

...

<main id="maincontent">
<h1>Heading</h1>
<p>This is the first paragraph</p>
</main>
</body>
{% endhighlight %}

## ARIA Roles

WAI-ARIA (Accessible Rich Internet Applications or ARIA) is a W3C protocol for enhancing and supporting accessibility of scripted and dynamic content. ARIA enhances accessibility of interactive controls (such as tree menus, drag and drop, sliders, sort controls, etc.), provides content roles for identifying page structure (navigation, search, main content, etc.), areas that can be dynamically updated (called "live regions" in ARIA), better support for keyboard accessibility and interactivity, and much more.

[Read more about ARIA].

WAI-ARIA provides the ability for developers to specify roles for document areas (and many other things). The available Document Landmark Roles are:

<h3>Banner</h3>

Site-orientated content, such as the name of the web site, title of the page, and/or the logo.

{% highlight html %}
<div role=”banner”>
{% endhighlight %}

### Navigation
The area that contains the navigation links for the document or web site.
{% highlight html %}
<ul role="navigation">
  <li>...</li>
</ul>
{% endhighlight %}

### Main
The main or central content of the document.

{% highlight html %}
<div role="main">
{% endhighlight %}

### Search
This section contains the search functionality for the site.
{% highlight html %}
<form role="search">
{% endhighlight %}

### Article
Stand-alone content that makes sense out of context from the rest of the document. Examples might be a blog posting, a comment on a blog, a forum post, etc. Specifically, a blog posting might be identified as an article and individual blog comments might also be marked up with a role of article within that blog posting.

### Complementary
Supporting content for the main content
{% highlight html %}
<ul role="complementary">
  <li>...</li>
</ul>
{% endhighlight %}

### Content Info
Informational child content, such as footnotes, copyrights, links to privacy statement, links to preferences, and so on.

<div class="text-center">
	<img src="/images/posts/a11y/aria-roles.jpg" alt="Display of where the ARIA role tags go, like banner, navigation, main, complementary etc.">
</div>

### Tab Index

The tabindex attribute allows web developers to customize the tab/navigation order of web content. Most of the time, tabindex is not necessary. It should only be used in cases where the default tab order is not ideal and when the tab order cannot be changed by rearranging items in the content and/or by altering the style sheet to reflect the best visual arrangement.

The tabindex attribute is added to HTML elements, as in the example below:

{% highlight html %}
<a href="http://webaim.org/" tabindex="1">WebAIM.org</a>

<form action="submit.htm" method="post">
<label for="name">Name</label>
<input type="text" id="name" tabindex="2">
<input type="submit" id="submitform" tabindex="3" value="Submit">
</form>
{% endhighlight %}

### Hiding elements from screen readers

Some elements are only helpful for sighted users. If these elements are not hidden, often content is repeated like separate desktop and mobile navigation menus.

To hide elements with ARIA use the following attribute:

{% highlight html %}
aria-hidden="true"
{% endhighlight %}

[Read more about hiding elements]. 

## Keyboard accessibility for links

One of the most serious barriers is to create links that go nowhere. Developers sometimes use JavaScript to create dynamic menus that drop down when the user hovers over certain links with the mouse. In some cases, the link itself goes nowhere at all, and its only purpose is to expose the links in the drop-down menu, which do have real destinations.

<p><span class="emphasise">Do not do this: <pre><xmp><a href="#" onmouseover="dropdownmenu()">Products</a></xmp></pre></span></p>

## Language
Always define the language at the top of the page (shown below):

{% highlight html %}
<html lang="en">
{% endhighlight %}

And, in block quotes when the language changes(shown below):

{% highlight html %}
<blockquote lang="de">
{% endhighlight %}

## Headings

Pages should be structured in a hierarchical manner, generally with one 1st degree headings (<h1>) being the most important (usually page titles or main content heading), then 2nd degree headings (<h2> - usually major section headings), down to 3rd degree headings (sub-sections of the <h2>), and so on. Technically, lower degree headings should be contained within headings of the next highest degree (i.e., one should not skip heading levels, such as from an <h2> to an <h4>, going down the document).


[WebAim]:http://webaim.org/articles/
[WCAG 2.0]:http://www.w3.org/TR/WCAG20/
[Read more about ARIA]:http://webaim.org/techniques/aria/
[Read more about hiding elements]:http://webaim.org/techniques/css/invisiblecontent/
