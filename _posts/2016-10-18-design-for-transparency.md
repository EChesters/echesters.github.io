---
layout: post
title: Designing for Transparency
description: Humans are lazy, and we often choose the quickest and easiest journeys to complete our goals. So our websites need to be clear, make the complex seem easy and be as visible as possible.
---

<p class="summary">Recently I wrote <a href="/2016/09/18/psychological-blindness-UX.html" lang="en">an article on the psychological phenomenons of blindness</a> and how to address them in user experience. But the concept of visibility and being transparent in design is so much more. Designing for the opposite of clarity for users can easily turn into a dark pattern, tainting your reputation with users.</p>

<p><span class="sidenote">When something doesn’t look like what is expected it’s hard to wrap your head around it. Once as a child my mum gave me green rice pudding, using food colouring. I couldn’t bring myself to even try it. It looked vile. I knew food colouring wouldn’t affect the flavour but mind over matter prevailed. (My mum couldn’t eat it either).</span></p>

## Users don't pay attention

Humans are lazy, and we often choose the quickest and easiest journeys to complete our goals. But that does not mean our brains will engage when we’re trying to complete said goals. Krug’s ‘Don’t Make Me Think’ is a classic because it hits the nail on the head. Often we don’t get to choose mind over matter. We simply don’t see what we don’t see because we’re not paying attention.

Even today there are a lot of elements which are easily lost in the design of pages and leave us second guessing. Ghost buttons are often overlooked, especially those inside a carousel, with alternating background colours. Buttons should look like buttons! Elements need to convey what they are, and from a quick glance. We shouldn't be second guessing components nor using “on-trend” aesthetics as an excuse for poor usability. 

<p><span class="sidenote">“Jesus Christ. It’s like a test! At this point I would have gone and had a cup of tea if I was at home.” - Participant struggling to find the reserve button amongst the 7 call to actions on the page</span></p>

There are many psychological factors at play, from attention span, to plain ignoring what's in front of us. While you can’t cheat psychology there are ways to design for clarity, reduce mistakes and remove the dark patterns. Be bold, be clear and place the information where it’s expected and relevant.

### Dark patterns

From a recent experience, I've seen a dark pattern; hiding prices in order for you to spend more money. UberEats, the recently new food delivery app, lets you know when items cost extra when you’re selecting your food. What they don’t show you is the exact price change on the menu or your order.

<figure>
	<img src="/images/posts/clarity/sauce.png" alt="Screenshot of UberEats menu displaying all sauces at the same price, even though they charge extra for some sauces" class="small position central">
	<figcaption>Screenshot of the menu serving the sauces I bought. Note the “P and B BBQ” sauce is 50p</figcaption>
</figure>

From here the experience gets worse. When reviewing orders, the subtotal seems to be plucked out of nowhere and doesn't make any sense. Sauces here are displayed at 50p and is still shown to be at 50p even when they’re actually £1.00. After remembering what came with the meal, the P and B part of the item refers to two different sauces.

<figure>
	<img src="/images/posts/clarity/ubereats-2.png" alt="Screenshot of UberEats receipt charging for two sauces, but displaying 1 50p charge" class="small position central">
	<figcaption>Screenshot of the receipt charging for two sauces, but displaying 1 50p charge</figcaption>
</figure>

Their customer service offers no resolution for mistakes in order calculations. Their solution is to tell the user to be more vigilant. But how can you expect your users to magically know the information you’re physically just not giving them?

<figure>
	<img src="/images/posts/clarity/ubereats-3.png" alt="Customer service response of: The issue is similar to the first one, the price at £3.50 for the small portion (3 wings) and the £2.45 extra is because it was the medium portion (5 wings). So if you let me, I would suggest that from no on you double check your prder and be specially vigilant about those marks in the options that seem something like plus 50p or any other amount in any restaurant servicing its clients through UberEats" class="position central">
	<figcaption>The response from the UberEats customer service</figcaption>
</figure>

Why hide the price of items? Time and time again in user interviews, we hear budget and pricing being top priority, regardless of which website we're testing. Hiding information as important like prices will definitely affect how trustworthy your app seems. This not only hurts your app user experience but your brand experience too.

## Colour and Contrast

Colour and contrast play a huge role in what users see. Contrast, contrast and more contrast. It is unbelievable how often this is disregarded. This next example alone lead me to rekindle this particular post from its brain dump stage. 

<img src="/images/posts/clarity/bershka-1.PNG" alt="Bershka's shipping message in low contrast which is hard to read" class="position central">

<p><span class="emphasise">If you have to squint or tilt your screen to try and see something, you’re doing it wrong. 
</span></p>

<p><span class="sidenote">Dear Bershka, Why are you hiding your free shipping from us?</span></p>

As someone currently wearing a Bershka top from Romania, I am your audience! People love most things which are free, and this definitely applies to free shopping. As an e-commerce business why would you hide this, not only contrast but behind other text?

While I can read this, I know there are plenty of users with visual impairments who rely on high contrast. This is so difficult to read and is easily fixed. Always test your branding and styling for contrast and other accessible standards. Your brand styling is the foundation of your design. If there are issues in branding, there will be issues throughout.

## The Fold

The Fold, the invisible and debatable line at the bottom of a screen, which defines the highest priority of a website. The fold, which does and does not exist at the same time. When a page stretches beyond the screen size, not all the content is visible at once, so there is a fold. But screen sizes change and it isn't something you can pin point. Different screen resolutions and sizes affect where and if there is a fold. While you can set the size of your page to be the height of the viewing window, the moment your users scroll is the second that they've created a whole new fold.

The physical device users are on also have a huge impact on scrolling. I am a “lucky” person who uses a Windows machine at work and a Mac at home. And there is a difference in my scrolling behaviour between devices. My Mac’s touchpad works like a dream. I can flick, swipe, pinch to zoom. I could scroll forever and ever. Yet using my mouse scrolling wheel for Windows is unbearable. To the point where I move my mouse to the scroll bar and manually move the page, or I give up and hedge my bets with the trackpad.

In user testing we often see users scrolling. When our participants don’t scroll further, it’s when they’ve scrolled to a point where the rest of the page looks like a footer. We’ve found this to be quite common on retail sites and more so on mobile. Banners between sections often separate relevant and important product details.

<p><span class="sidenote">“I thought when I got to here I was at the bottom. Like the ads at the bottom. I hadn’t noticed the description was at the bottom and further down” - Participant during user testing</span></p>

### Entice users to scroll

While studies have shown over 75% of users scroll, you still need to entice users to do so. A large part of the enticement to scroll comes from the layout. If the user is lead to believe that the information below what they’re seeing is relevant to their needs, they will seek it.

A quick way to do this is to use misalignment. Just like how Pinterest leaves sections cut off so the user scrolls to unveil that content with more sections peeking above the fold. The more dumb and obvious place the information cuts off, the more likely the user will realise they need to scroll. 

## Forms

There’s a special place in every UXer’s heart for forms. They are the necessary evil of what feels to be 99% of web pages. The number one crime for a lack of clarity on forms is the behaviour of information around fields.

### Keep labels outside of fields

The need for a smaller form quickly lead to labels being placed inside text fields. Of course as soon as you click into the field to type, you lose the field’s purpose. Users now have to remember what it asked for and its format. At first this sounds simple. But when you consider what our sites compete with in a user's environment, this information is easily forgotten. Keyboard focused users often only look down and enter information that they are expecting to enter. They seldom look up to read form labels. Non-native speakers using the form also have the extra burden of remembering words they’re not familiar with or vaguely understand. 

### Place hint text where relevant

Hint text also has the same issue of disappearing because it’s often placed inside the field as a placeholder. Anything that’s designed to be helpful becomes redundant the moment it disappears when it’s needed. Placing hint text at the side of the field allows for guidance throughout the process. (To the right side of left-to-right languages and the left for right-to-left languages). A great example of this is where we see password requirements. Also placing guidelines to the side of the field also gives you much more room for more than a single line. Having the help text appear relevant to the selected, means the information displayed is relevant. Take ASOS as an example.

<img src="/images/posts/clarity/asos.png" alt="ASOS as an example of a good form" class="medium position central">

ASOS give reasons as to why they're asking for particular data like emails, help text is underneath the field in line of sight, like password requirements. 

## Clarity in language

Jargon is one of those things to look out for, which is quite difficult to see for us when we see it every day. Domain specific language hinders the clarity in your experience in a number of ways. It’s usually not the language your users are using, so skimming for what they need takes longer.


The next culprit are links and buttons. They’re not helpful to anyone being one word or repeated on the same page, which we see more often than not. They also don’t help us when they’re five words long and don’t actually contain the words we skim for. For example, “Sign up for our Total Flexibility Plan” is not as easy or quick to read as “Buy insurance”.

<figure>
	<img src="/images/posts/clarity/curvissa.png" alt="Curvissa's newsletter repeating Click Here, making it hard to skim">
	<figcaption>Curvissa’s email includes numerous “Click here” links, meaning you have to skim around the link to know what each one does</figcaption>
</figure>

Here is where Information Architecture (IA) plays a huge role. Testing the IA reveals the language your audience are using and where they expect to find the information. The findability, organisation and labeling all come from good IA, and provides a lot of clarity in language. 

## Takeaways

Clarity comes from different aspects of UX. From visible clarity in contrast between foreground and background, to just plain displaying the information. 

**Contrast -** the minimum contrast ratio is 4.5:1 between elements

**Display information -** display all content, especially when it comes to prices and legal notices

**Forms -** keep all the relevant information visible at all times where it’s needed

**Language -** use the language your audience is using for consistency 

A visible and clear design is a trustworthy experience. 

