---
layout: post
title: Forms - Accessibility Code Snippets
description: Resource post for my team at the Accessibility hackathon, 18th and 19th March
image: "/images/posts/TV-1.jpg"
---

## Forms

### Keyboard accessible forms

Be careful in your use of JavaScript to manipulate form data, set focus, change form elements, or submit forms. Each of these can make the form difficult or impossible to complete or understand using the keyboard alone. Always test the web site forms for keyboard accessibility using NVDA screen reader.

### Legend and fieldset

Groupings of form controls, typically groups of related checkboxes and radio buttons, sometimes require a higher level description (such as "Shipping Method" for a group of shipping option radio buttons). This descriptive text can be associated to the group of form controls using <code><fieldset></code> and <code><legend></code>. The <code><fieldset></code> identifies the entire grouping and <code><legend></code> identifies the grouping's descriptive text. Using <code><fieldset></code> and <code><legend></code> ensures that the text description is read to screen reader users when the grouping is navigated to.

### Text inputs

Always include labels for text fields and areas, which are not inside the field as a placeholder.

#### Text fields

{% highlight html %}
<label for="name">Name:</label>
<input id="name" type="text" name="textfield">
{% endhighlight %}

#### Text areas

{% highlight html %}
<label for="address">Enter your address:</label><br>
<textarea id="address" name="addresstext"></textarea>
{% endhighlight %}

### Checkboxes

{% highlight html %}
<fieldset>
  <legend>Select your pizza toppings:</legend>
  <input id="ham" type="checkbox" name="toppings" value="ham">
  <label for="ham">Ham</label><br>
  <input id="pepperoni" type="checkbox" name="toppings" value="pepperoni">
  <label for="pepperoni">Pepperoni</label><br>
  <input id="mushrooms" type="checkbox" name="toppings" value="mushrooms">
  <label for="mushrooms">Mushrooms</label><br>
</fieldset>
{% endhighlight %}

### Radio buttons

{% highlight html %}
<fieldset>
  <legend>Choose a shipping method:</legend>
  <input id="overnight" type="radio" name="shipping" value="overnight">
  <label for="overnight">Overnight</label><br>
  <input id="twoday" type="radio" name="shipping" value="twoday">
  <label for="twoday">Two day</label><br>
  <input id="ground" type="radio" name="shipping" value="ground">
  <label for="ground">Ground</label>
</fieldset>
{% endhighlight %}

### Select menus

{% highlight html %}
<label for="favcity">Choose your favorite city?</label>
<select id="favcity" name="select">
  <option value="2">Buenos Aires</option>
  <option value="3">Delhi</option>
  <option value="4">Hong Kong</option>
  <option value="5">London</option>
  <option value="7">Moscow</option>
  <option value="8">Mumbai</option>
  <option value="10">Sao Paulo</option>
  <option value="11">Tokyo</option>
</select>
{% endhighlight %}

### Select menus - Grouped

{% highlight html %}
<label for="favcity2">Choose your favorite city?</label>
<select id="favcity2" name="favcity2">
  <optgroup label="Asia">
    <option value="3">Delhi</option>
    <option value="4">Hong Kong</option>
    <option value="8">Mumbai</option>
    <option value="11">Tokyo</option>
  </optgroup>
  <optgroup label="Europe">
    <option value="1">Amsterdam</option>
    <option value="5">London</option>
    <option value="7">Moscow</option>
  </optgroup>
  <optgroup label="North America">
    <option value="6">Los Angeles</option>
    <option value="9">New York</option>
  </optgroup>
  <optgroup label="South America">
    <option value="2">Buenos Aires</option>
    <option value="10">Sao Paulo</option>
  </optgroup>
</select>
{% endhighlight %}

### Buttons

{% highlight html %}
<input type="submit" name="submit" value="Submit Search">
<input type="reset" name="reset" value="Reset">
<button>Activate</button>
{% endhighlight %}

### Image buttons

{% highlight html %}
<input type="image" name="submitbutton" alt="search" src="submit.png">
{% endhighlight %}

## Error feedback for fields

### Required form fields

{% highlight html %}
<label for="firstname">First Name 
<span style="color:red">(required)</span></label><br />
<input type="text" name="firstname" id="firstname" />
{% endhighlight %}

### Error recovery

If either client-side or server-side validation detects errors in the form, then there is a 3-step process for ensuring usable and accessible error recovery:

<ul>
  <li>Alert the user to the presence of the error in an apparent and accessible manner.</li>
  <li>Allow the user to easily access the form controls that need to be modified.</li>
  <li>Allow resubmission and revalidation of the form.</li>
</ul>

### ARIA - Invalid

Regardless of the mechanism used to identify and recover from form errors, <code>aria-invalid="true"</code> should generally be set on each invalid form control. This attribute causes screen readers to identify the control as being "invalid" or in need of attention.
