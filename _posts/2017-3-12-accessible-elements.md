---
layout: post
title: Site Elements - Accessibility Code Snippets
description: Resource post for my team at the Accessibility hackathon, 18th and 19th March
image: "/images/posts/TV-1.jpg"
---

## Frames and iFrames

Example frame accessible code:

{% highlight html %}
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">
  <head>
  <title>A page that contains frames</title>
  </head>
  <frameset cols="15%, 85%">
    <frame src="menu.html" title="Navigation menu" name="menu">
    <frame src="content1.html" title="Main content" name="content">
    <noframes>
      <p>This frameset document contains:</p>
      <ul>
        <li><a href="menu.html">Page navigation</a></li>
        <li><a href="content1.html">Main content</a></li>
      </ul>
    </noframes>
  </frameset>
</html>

{% endhighlight %}

## Image alternative Text

The following images require alt text:

<ul>
  <li>Photograph and illustration images</li>
  <li>Buttion/navigation images</li>
  <li>Next/previous buttons</li>
  <li>Form image buttons ( e.g. <code>&lt;input type="image" alt="Submit Search"></code> )</li>
  <li>Icons (including PDF icons for example)</li>
  <li>Decorative images (e.g. decorative line/separator)</li>
  <li>Image maps</li>
  <li>Background images</li>
  <li>Logos</li>
</ul>

## Videos

### Captions

Common web accessibility guidelines indicate that captions should be:

<ul>
  <li><b>Synchronized</b> - the text content should appear at approximately the same time that audio would be available</li>
  <li><b>Equivalent</b> - content provided in captions should be equivalent to that of the spoken word</li>
  <li><b>Accessible</b> - caption content should be readily accessible and available to those who need it</li>
</ul>

Turn caption on, on a website, automatically with <code>"cc_load_policy=1"</code> turns captions on by default.

## Tables

The example below shows how to associate data cells (created with TD) with their corresponding headers by means of the "headers" attribute. The "headers" attribute specifies a list of header cells (row and column labels) associated with the current data cell. This requires each header cell to have an "id" attribute.

{% highlight html %}
<table border="1" 
       summary="This table charts the number of
               cups of coffee consumed by each senator,  
               the type of coffee (decaf or regular),
               and whether taken with sugar.">
 <caption>Cups of coffee consumed by each senator</caption>
 <tr>   
     <th id="header1">Name</th>
     <th id="header2">Cups</th>     
     <th id="header3" abbr="Type">Type of  Coffee</th>   
     <th id="header4">Sugar?</th>
  </tr>
  <tr>  
    <td headers="header1">T. Sexton</td>  
    <td headers="header2">10</td>
    <td headers="header3">Espresso</td>
    <td headers="header4">No</td>
  </tr> 
  <tr>  
    <td headers="header1">J. Dinnen</td> 
    <td headers="header2">5</td>
    <td headers="header3">Decaf</td>
    <td headers="header4">Yes</td>
  </tr>
</table>

{% endhighlight %}

#### Accessible data table

The example below shows how to associate data cells (created with TD) with their corresponding headers by means of the "headers" attribute. The "headers" attribute specifies a list of header cells (row and column labels) associated with the current data cell. This requires each header cell to have an "id" attribute.

{% highlight html %}
<table border="1" 
       summary="this table charts the number of
                   cups of coffee consumed by each senator,  
                   the type of coffee (decaf or regular),
                   and whether taken with sugar.">
   <caption>cups of coffee consumed by each senator</caption>
   <tr>   
      <th id="header1">name</th>
      <th id="header2">cups</th>     
      <th id="header3" abbr="type">type of  coffee</th>   
      <th id="header4">sugar?</th>
   </tr>
   <tr>  
      <td headers="header1">t. sexton</td>  
      <td headers="header2">10</td>
      <td headers="header3">espresso</td>
      <td headers="header4">no</td> 
   </tr> 
   <tr>  
      <td headers="header1">j. dinnen</td> 
      <td headers="header2">5</td>
      <td headers="header3">decaf</td>
      <td headers="header4">yes</td>
   </tr>
</table>
{% endhighlight %}

