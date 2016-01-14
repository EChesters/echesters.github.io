---
layout: post
title: Why Be Accessible?
description: Despite the technology we have today accessibility is still an issue and still a non-functional requirement that you have to sell to your stakeholders and clients. This post is a take on why that shouldn't be the case. 
---

Barriers suck. Technology has evolved so much in terms of removing barriers for everyone, over borders, languages and disabilities. Yet even on the most popular of websites barriers still exist, and they continue to exclude those who need technology the most.

Society is making advances all the time, especially when it comes to technology. Look at the paralympics. Some could argue their legs are better than those who are abled. By using artificial limbs, those considered “disabled” are able to compete, thus a barrier has been lifted. The point here is that technology even more so should be uplifting these barriers more and more and instead I hear user feedback of big brands websites saying they suck.

> Accessibility is important, but somewhere along the way it got an undeserved reputation for being ugly, costly, and driven only by technical-compliance requirements.

<div class="author"><p>Derek Featherstone, Accessibility as a Design Tool</p></div>

I could not agree more with this statement. I’ve only recently started looking into accessibility and early on in my research did I find out this statement and the whole attitude towards accessibility. But the more you look into this area the higher the benefit is at the end, and for more users than you might initially think. Accessibility = Usability. Not even just usability, but all it takes is good standards. For example, screen readers use your HTML structure to read what the page is about; so having a title tag in the middle of a paragraph logically/structurally makes no sense; never mind accessible.

Being accessible does not mean going through every disability known to man to do endless amounts of research of who might struggle with your website. It does not mean that it is one person’s job to sit there and make sure everything on your site/software is accessible. It’s impossible to be accessible for absolutely everyone, but there are numerous things which everyone in the team can do to be more accessible, and to raise awareness of the good practices which increase accessibility. You know as well as I do that accessibility is usually an after thought (unless you’re providing a government service), but that does not mean it’s too late. You have to start somewhere!

Here are a few tips I’ve recently found, which I think are reasonable, short and practical to help become accessible. But it should be said that accessibility is another design practice which should be monitored but alongside everything else you monitor in your site’s life cycle. It’s not a one time, enter a link into an online tool, fix the errors you can be arsed with and then BOOM, you’re magically accessible. You do need to understand how disabled users use their software, to use your software and what they think of it. Yes this is difficult but for a good user experience you should be user testing anyway.

### Alt Tags

This is definitely a HTML standard which is good practice. All images must have an alt tag, whether that be empty or not. The alt tag must fill in the information that is lost to a blind person, that otherwise would be provided to your users who can see it. This blog really explains it well with examples. If half the information of the image is explained in the surrounding text, then repeating the information in the alt tag is a bit redundant, so keep the description short and sweet but still relevant to what the image is showing. But why would you ever just stick an empty alt tag on there? Surely that’s redundant. Well no. Screen readers understand that websites use images in a purely decorative manner, and that’s fine. But someone using said screen reader does not need to be told that the image there is decorative. When no alt text has been set, screen readers will read the file name as an alternative, so that the site is accessible as possible. Yeah… not the best approach since we’ve all seen what file names can look like “gjhgyeygfqfrf21.jpg” or “2014-09-23.jpeg-large”; beautiful. An empty alt tag suggests the image is decorative and can be ignored.

### Sensory Characteristics

Do not rely on one sensory characteristics for special information; especially links. For anyone, this can be a usability flaw when you can’t find necessary information quickly enough. For a lot of users using multiple websites at a time; especially during a search, being able to see the information they need quickly and obviously makes a huge difference. If Wikipedia decided to make their links one shade lighter than the text without another obvious tell-tale, their page bounce would increase tenfold, without a shadow of a doubt. This applies to the information that you have on your sites. If a user doesn’t see that your page is relevant they won’t sit there decoding if it is. I’ve got a bazillion other websites I could be on right now, that probably have this usability feature.

Moving on from websites, and more into mobile accessibility, having the option to allow for haptic feedback when your app needs to notify its owner of a change, increases its usability immensely.  But be careful not to overuse this, as although the option is great if you remove the choice then this may just become annoying. Personally, I find the more feedback there is, in terms of audio, visual and touch; the more serious the notification – so choose your combinations wisely.

### Content

Firstly; I mean automatically playing content. Whether this be video or audio, this is just plain annoying. But from a health and safety point of view, if your content automatically plays, this can be overwhelming, irritating and distracting for those with ADHD or social issues. Not only is this difficult for disabled people to sometimes cope with, but even in general if something is playing automatically and you have lots of tabs open or it’s below or above the fold where you are on the page; this breaks the user’s flow from completing their task which only makes the experience frustrating. Google Chrome’s little audio symbol on noisy tabs seems like a God send now, in comparison to what it was like before. Why is this a new thing though!? Anyway…

Secondly in terms of content; especially video content, always make sure you provide your own captions or test automatic captioning. I recently tested a video on a site where the person speaking had a strong Indian accent. I could understand what was being said, but YouTube’s captioning, did not. The subtitle went a little like this:

> “he” .. “anxiety” .. “mother he did” .. “shit”

Swearing at your users is not advised, especially when they can’t know what is actually being said. The video was actually talking about Continuous Integration, so given this context no one would be expecting the word “shit” to be in there. I know it’s much more time consuming peeing about writing your own captioning; I for one have never had to mess around with captions but at the very least test the automatic ones! Captioning as well provides usability for those users who can’t listen to the video at the time, given no headphones and they don’t fancy annoying everyone else on a train. The actual benefit of captioning is quite high, despite its high cost in the first place.

### Personas

So an easy approach to accessibility is to treat the subject like any other design process. So in the previously mentioned podcast, it talks about bringing in accessible features as you would with other functionality. Take the following persona scenario as an example:

Catherine needs to be able to view her images on her photo sharing website.
This functionality seems obvious, viewing photos on an image sharing site. Now take this persona as an example:

Terrence needs to view his images on her photo sharing website. As his hand tremors, he will need to access each image using the keyboard only.
There’s a huge difference in bringing in functionality which happens to be accessible. These matters don’t need to be addressed as something completely different, nor do they need an expert to address. These are basic functional requirements, just from a different user group’s perspective. Doing this functionality in mind when building software in the early project life span helps to reduce cost.

Overall accessibility is a win-win, and even more-so when it’s done right. Same as technical debt and good practices, it’s something which needs to be brought in during the project lifecycle, rather than tried to be fit into a system already “sort of finished”. Usability is also increased, and so is the user experience. Sites are less frustrating, less annoying and more enjoyable to use. These are some very simple things to consider and yes there are probably hundreds more, but like being 100% accessible, capturing all of them is impossible. So feel free to use this as a starting point at least and I will try and add more!