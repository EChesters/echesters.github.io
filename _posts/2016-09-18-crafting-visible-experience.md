---
layout: post
title: Crafting a Visible Experience
description: Is a button does not look like a button, will people click it? From inattentional and change blindness, discover here the pschological phenomenons which affect how our users don't pay attention and are completely blind to what we put in front of them. Also find out how to solve and test for these issues in your designs. 
image: "/images/posts/visibility/vision.jpeg"
---

<p class="summary">"If a tree falls in the forest and nobody is around to hear it, does it make a noise?” - Pastor George Berkeley, 1710</p>

<span class="emphasise">If a button does not look like a button, will people click it?</span>

Something is as good as not there if people cannot see it. From being physically obscured, to plain ignored, if you can't see it, it might as well not be there. While you can test if an element looks how it’s supposed to, this does not guarantee that your users see it. Eye tracking reveals users are looking at something, but their actions completely contradict this.

From psychology to plain laziness, check out the ways in which we are all blind and how we can build the experience with this in mind.

## Different types of blindness

### Banner blindness

The most common form of psychological blindness is banner blindness. The phenomenon where people ignore anything that is or looks like an advert on a web page. Adverts are all around us, with barely any useful information in them so we’ve learnt to filter them out. This includes anything that looks like an ad, whether it actually is or not. 

Due to economic reasons, profits on Chinese websites predominantly came from adverts. So to get around banner blindness their [adverts became flashier] and more in your face. While their economical situation may have changed, this pattern has become embedded in Chinese web design. Navigation is often filled with animations like on [banggo.com] and [jumei.com].

<div class="col-xs-12 col-sm-9 position central">
	<img src="/images/posts/visibility/chinese-1.gif" class="margin-horizontal" alt="Chinese navigation option with a bouncing new notifier">
	<img src="/images/posts/visibility/chinese-cart.gif" class="margin-horizontal" alt="Chinese cart icon which fills up with items">
	<img src="/images/posts/visibility/chinese-2.gif" class="margin-horizontal" alt="Chinese navigation option with floating icons over the text">
</div>

It’s interesting that in user testing, similar banners on Western websites are also overlooked. It is a hard comparison since the following sections don’t move, but in testing they were not noticed once.

<img src="/images/posts/visibility/navigation.png" alt="Navigation bar with new icon above categories">

### Change blindness

Change blindness is a similar phenomenon where we don’t detect changes. Whether they're in our environment, on websites or directly in front of our faces. [The Invisible Gorilla] reveals many extensive experiments, where high percentages of participants did not notice changes. These ranged from people changing clothes, to completely different people at ticket windows.

As a quick experiment [watch this Chemical Brothers video], before reading on. Being honest, how long did it take you to notice that her limbs had changed? I have watched the video numerous times, yet I still don’t notice when her body changes, until the dancer looks at her changed limb.

Change blindness is just one reason why automatically rotating carousels are the devil. [Nielsen Norman ran an experiment with carousels] and recorded the details users could recall from the page.

<span class="emphasise">The user's target was at the top of the page in 98-point font. But she failed to find it because the panel auto-rotated instead of staying still. - Nielsen Norman</span>

Not only do carousels resemble banners, when they change it forces users to remember content in other sections. Users need to engage with the carousel and view the different sections. Otherwise previous information is likely forgotten or noticed. Personally, [I don’t recommend carousels at all], but if necessary, its navigation and interactions should stand out.

With personalisation and adaptive content becoming popular, change blindness is more relevant than ever. I would love to continually test with users as they grow familiar with a service, but one where they don't expect content to change. Services unlike Netflix, which are often updated and personalised. I expect new content but I don’t sit there thinking, “this recommendation is so me!”. For websites where personalisation is not expected or obvious, do users notice the differences? In a scenario where someone uses another machine, do they recognise that the site has changed to a 'generic' version? Personalisation is purposefully inconsistent across people, otherwise what is its point? Despite being, arguably immature, there are already blogs on how users do notice changes and [how to not make them creepy]. 

How we accommodate for change blindness depends on our users, how attentive they usually are and which areas they’re not noticing. Using empathy maps to understand the mindset of where and when people use your app, is a good starting point. From this we can estimate how much cognitive bandwidth someone can give to our app. A commuter, already stressed and distracted with travel, is less likely to notice changes than someone casually browsing at home. Here we can work out a more obvious tell tale of there being new information.

Changes are most lost when we’re least expecting them. Pages which dynamically load content, like filtered results, are often unnoticeable, when content changes. Even when users are expecting updated results, if they can’t see when it has changed, the new information is overlooked. Messages informing users of change should be in the areas where they’re already paying attention. Otherwise the message in itself is another change.  It also helps to include moving icons to indicate when something is happening and when it is finished. 

You can also test with yourself or colleagues to see if people notice changes, by using the squint test. This exercises what someone sees on the page from a distance and highlights what stands out. Eye tracking is also a good indicator to see which areas users are paying attention to. It shows where the eyes are focusing once they’ve triggered a change. Of course without context it’s hard to know if they've acknowledged the change. Using questionnaires or surveys after completing the task will help test their memory.

#### Change blindness blindness

The experiment by Simons and Levin in 1997 for The Invisible Gorilla not only lead to discovering how people are prone to missing the obvious when concentrating, but also our own attitudes to change blindness. The following study by Levin and Simons demonstrates participant’s level of confidence in noticing changes: 

<span class="emphasise">[Of the three changes] 76.3%, 90.5%, and 69.5% of subjects in the current experiment estimated that they would notice the same changes.</span>

The end result showed that 0% of their participants saw all 3 changes in the film shown. 

Not only do we inevitably suffer from change blindness, but we are in denial to our blindness. From this, David Levin birthed the term ‘Change Blindness Blindness’; the belief that we would notice obvious changes before being pointed out.

#### Change blindness across cultures

Experiments show how humans across cultures suffer with these psychological phenomenons in different ways. [An experiment by Nisbett and Masuda], ran with American and Japanese participants demonstrated the different ways in which we analyse situations. Offering a picture and changing elements in both the foreground and background, they tested where the different cultures focused their attention and what they failed to notice. The Westerners consistently noticed changes in specific objects rather than in the background or scene of the image. They also tended to be more analytical, whereas the Far East Asian culture tended to notice things holistically.

I would love to run my own experiments expanding this idea to consider high and low context as a factor. The American participants failed to see changes in the environment. This to me suggests they didn’t take surroundings into account, due to their low context nature. On the flip side, Japanese culture is high context. This could also explain why Japanese participants focused more on background than central objects. 

### Inattentional blindness

[Inattentional or perceptual blindness] is the phenomenon where we don’t see what is in plain site, due to a lack of paying attention. Most people consider themselves busy, so when users are using an app it’s to achieve a goal, and quickly.
During user research, it’s interesting to see someone struggle to find something, when eye tracking shows they’re looking right at the element.
I even added a line to my user research introduction to explicit state; “I cannot help you if you struggle with the app” because of how frustrating and common this was.

The Invisible Gorilla, Don’t Make Me Think and Thinking Fast and Slow all vocalise that we just aren’t paying attention. In an age where our users constantly flick between apps, we are competing like never before for users’ attention. How we build websites and how they are actually used are often misconstrued. In Krug’s Don’t Make Me Think he uses a similar example to the following to explain the differences of how we view the same page depending on our goals.

<div class="images">
	<figure class="col-xs-12">
     	<img src="/images/posts/visibility/bbc-original.png" alt="BBC original website">
     	<figcaption>Original BBC website shown as intended for use</figcaption>
     </figure>
     <figure class="col-xs-12">
     	<img src="/images/posts/visibility/bbc-sport.png" alt="BBC website with all sections blurred apart from stories related to sport">
     	<figcaption>How users see the BBC website when searching for stories related to sport</figcaption>
     </figure>
	<figure class="col-xs-12">
     	<img src="/images/posts/visibility/bbc-weather.png" alt="BBC website with all sections blurred apart from stories related to weather">
     	<figcaption>How users see the BBC website when searching for stories related to weather</figcaption>
     </figure>
</div>

#### Cultural attention

Experiments which test what we don’t pay attention to also discover what we do pay attention. An experiment run by Masuda et al. presented findings which showed attention differences between East Asian and North American participants. Japanese participants noticeably focused their attention on peripheral figures with their judgements influenced by background changes. Whereas, in a similar experiment, by Chua, Boland and Nisbett (2005), American participants focused their attention on central objects sooner and for longer. The American participants also made less eye movements than their East Asian counterparts.

## Defeating our blindness

So how do we overcome our psychological impairments? There is no definite answer to solve all types of blindness, which we encounter in our online adventures. As seen in user research, some simply don’t pay attention and others see elements straight away, often answering your “did you notice X?” in a tone implying it’s so clear it's common sense. 

It’s quite easy for blogs and books when discussing banner blindness to say “don’t make important stuff look like an ad”. Yet design is subjective so this isn’t an easy task, and context complicates further. Using retail sites as an example, there’s a thin line between what is perceived as a promotion, a product display or an advert. Testing doesn’t give you all the answers but it’s a great starting point. It offers insights from someone about what they didn’t notice (when prompted) and their guesses as to why.

Tackling change blindness is quite tricky. For content in carousels, just really reconsider what you’re gaining by having a carousel. In other scenarios, focus on how you’re notifying users when something has changed. Definitely don’t rely on colour alone. Not only is this not an eye catching enough change, those with colour blindness will have no way of knowing, no matter how hard they stare at the screen. Using icons may not completely fix the issue, but will improve the UX and increase your chances of noticing changes.

On the flip side of this, there is a way to know where our users are looking or at least scanning. [Design patterns] show us where our users are expecting content to be, including things like navigation. The F pattern as an example shows us where users scan on pages displaying search results or a list of blog posts. Use the different design patterns to place content and elements where users expect them. By also conducting competitor analysis, discover where your users are finding similar elements and keep locations consistent. Using tools like heat maps and running A/B tests will also show where users are clicking. This means there’s a high chance that the user has seen where they have clicked. These tools make it easier to see if people are going through the journeys or funnels designed to achieve their goals. While user testing can provide incomparable and richer insights into user behaviour, you can never predict the subset of users you test with. By using quantitative tools as well, you see the data of all your audience. At least those who are kind enough to not block your analytics!

## In Summary
There are many phenomenons which prevent us from seeing what we even want to see. In our new digital world where users are waiting for a Snapchat from a best friend or a new follower to boast about, why should they pay attention to our site? We have to prove to people why they should dedicate time of their lives to our services instead of competitors. Fighting against psychological instincts is not an easy challenge nor is it a conscious decision our users make. Gaining insights into user behaviour before, during and after using our app will help us gage how to structure web sites to provide for our users' needs on a subconscious level.

It’s interesting to note how culture impacts how we notice things and has a say in where we focus our attention. Despite these visual impairments being a part of how we behave, there is hope for our user experiences. Test your designs using quantitative and qualitative methods. Design for the skimmers, the tired or the drunk persona in us all. Remember this is time of our users' lives that they are dedicating to using our services. If people simply can’t see what we need, they have no choice to either abandon or resent how you made them feel. 


[their adverts became flashier]:http://www.slideshare.net/cxpartners/chinese-web-design-patterns-how-and-why-theyre-different/34-They_are_all_a_dverts
[banggo.com]:http://banggo.com/
[jumei.com]:jumei.com
[The Invisible Gorilla]:http://www.theinvisiblegorilla.com/
[watch this Chemical Brothers video]:https://www.youtube.com/watch?v=BC2dRkm8ATU
[Nielsen Norman ran an experiment with carousels]:https://www.nngroup.com/articles/auto-forwarding/
[I don’t recommend carousels at all]:http://shouldiuseacarousel.com/
[how to not make them creepy]:http://thenextweb.com/dd/2015/10/13/how-to-personalize-your-ux-design-without-being-creepy/
[An experiment by Nisbett and Masuda]:http://onlinelibrary.wiley.com/doi/10.1207/s15516709cog0000_63/epdf
[Inattentional or perceptual blindness]:https://en.wikipedia.org/wiki/Inattentional_blindness
[Design patterns]:http://vanseodesign.com/web-design/3-design-layouts/

