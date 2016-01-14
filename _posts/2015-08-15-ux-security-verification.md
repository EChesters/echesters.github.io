---
layout: post
title: Seven ways to improve verification for your users
description: Since a computer has never passed the Turing test, you’d think it was easy to tell if a bot was using your site and not a user. Yet fake Twitter accounts still exist and spam reigns our Tumblr comments. How many loopholes do we have to pass onto legit users before we lose them?
---
Since a [computer has never passed the Turing test], you’d think it was easy to tell if a bot was using your site and not a user. Yet fake Twitter accounts still exist and [spam reigns our Tumblr comments].

Verification [blogs like this CAPTCHA one] mentions how we’re burdening legit users with tasks which aren’t their problem. The blog then goes on to suggest “easier and more enjoyable tests”. Since when do I have to pass a test to join a service? More importantly, why am I asking my users to do the same? 

## CAPTCHA Forms
[CAPTCHAs are little boxes with distorted text], that you need to enter to prove you're human. The security element behind these forms is to provide a test that a human can pass but a bot can’t. For example when posting a comment, or creating a new account.

[CAPTCHAs] stop every user in their tracks. Yet for those who need accessible alternatives, they're an even bigger obstacle. Users relying on braille displays, there are no audio or visual ways of answering the form. A more inclusive UX needs to offer an alternative method. Yet the moment you add alt tags or anything a screenreader can access, you've made the process easier for a bot.

<div class="images">
	<img class="rounded landscape small" src="/images/posts/security-verification/original-captcha.png" alt="The first version of CAPTCHA forms, with random text in a box">
</div>

But are you hurting your user experience in the process? By using a third party captcha form we have no control over what the CAPTCHAs look like. The chances are you've even come across ones that aren't readable at all, like this one on hotmail.

<div class="images">
	<figure>
		<img class="rounded landscape small" src="/images/posts/security-verification/hotmail-captcha.png" alt="CAPTCHA text on hotmail.com where you can't tell if the last letter is a P or R">
		<figcaption>Is that last letter a P or R?</figcaption>
	</figure>
</div>

### ReCAPTCHA
If you've ever come across captchas, you've come across [reCAPTCHAs]. ReCAPTCHAs are a clever way of not only protecting sites from bots, but also digitise books. The text you "translate" is [helping decode books scanned], that computers can’t understand. So not only are you keeping those pesky bots at bay, you are also helping the Internet with translations.

<div class="images">
	<img class="rounded landscape small" src="/images/posts/security-verification/recaptcha.png" alt="A ReCAPTCHA form showing distorted text read in from somewhere like a book">
</div>

Despite being smart in the background, it still causes the same problems as the original CAPTCHA. It breaks up the user flow and leads to a lot of frustration. The accessibility issues also still stand, despite there being an accessibility button. Users with a cognitive impairment are not helped just because an audio alternative is available. 

### The new reCAPTCHA
Google actually realised the problem with CAPTCHAs and [redesigned a new ReCAPTCHA concept]. Bots are becoming increasingly better at solving CAPTCHAs, which lead to more complicated text. This meant that it was getting more difficult for users to solve. The new reCAPTCHA now analyses a user's entire engagement with the page, to determine if the user is legit. 

It's great to know that there is an accessible version for visually impaired users. Yet, sadly when trying to use it via keyboard only it was a little trickier. It took a few attempts to actually tab onto the checkbox. When I had to then select images from the grid relating to the given word, it was impossible to select anything.

<div class="images">
	<img src="/images/posts/security-verification/new-recaptcha-2.png" class="rounded portrait" alt="A new reCAPTCHA form showing distorted text read in from a door">
</div>

This doesn't solve the fact that we are still stopping users in their tracks and increasing their task load. However it is half way there to simplifying the issue. 

### Mathematical CAPTCHA
Even for a developed country, the [UK ranks low when it comes to numeracy skills amongst adults]. So it makes you wonder why CAPTCHA forms are now involving math equations. Cognitive impairments then go on to amplify the problem, rendering the experience inaccessible. Sure, they're "simple" sums a user could easily type into Google, but then that causes a drop off in your user journey. There's also a risk of making your users feel dense. 

<div class="images">
	<img class="rounded landscape small" src="/images/posts/security-verification/math-captcha.png" alt="math CAPTCHA showing 1 times 6">
</div>

*[There are no stupid users, only stupid interfaces.]*

Some sites like [Quantum Random Bit Generator], go as far as including these beasts of an equation:

<div class="images">
	<img class="rounded landscape small" src="/images/posts/security-verification/quantum-math-captcha.png" alt="A math CAPTCHA of a crazy equation using cos, pi and algebra">
</div>

I understand it's not your average Joe Bloggs website, but is that *really* necessary? In small print the site then goes on to say if you refresh you'll (probably) get an easier question. I refreshed a few times and none of the questions seemed to be simpler. Instead they got bigger, included more mathematical symbols and put me even more off. I would love to know the reasoning behind this UX design.

### Accessible CAPTCHA
CAPTCHAs are the most widely used method of keeping out spam and it’s a pity how many flaws there are. Even if we haven’t experienced them the above shows how others struggle. Yet there is an [accessible CAPTCHA], from the [American Foundation for the Blind]. This CAPTCHA works by giving an instruction that a bot couldn’t do. For example “Please type "hello" here” or “Please put the word horse in the box”. The tasks have multiple wording, meaning that it’s hard for bots to parse.

But is this really an accessible alternative?

*Just because is works with a screen-reader does not mean it’s accessible.*

Fair enough, the site does claim that it’s not a perfect solution. To me it’s long way off being accessible. It completely isolates those with poor numeracy skills, spelling skills, cognitive impairments, and who may struggle with a foreign language. We’re supposed to be excluding bots, not users!

### Ghost CAPTCHA
Out of all the CAPTCHAs that we’ve been through, my personal favourite has to be [Ghost CAPTCHA]. Ghost CAPTCHA will only force a user to decode text if they  have behaved in an abnormal manner. The plug-in monitors users’ behaviours through mouse movement, clicks and the time they complete the form.

<div class="images">
	<img class="rounded two left" src="/images/posts/security-verification/ghost-captcha-2.png" alt="shows a form with Ghost CAPTCHA but before a CAPTCHA form has been triggered">
	<img class="rounded two right" src="/images/posts/security-verification/ghost-captcha.png" alt="shows the CAPTCHA being shown on a form, because the form has been filled in too quickly or the user has filled in the honey pot">
</div>

This is great because the CAPTCHA form is only shown if the form is filled out in Guinness world record times. It’s removing the responsibility from the user until it believes it to be necessary. Unfortunately this doesn’t solve the accessibility problems as with every other CAPTCHA form. But if you’re going down the route of using a CAPTCHA form, this is the best one. It removes the responsibility from the user and doesn’t cause issues until it has to.

The difference between Ghost CAPTCHA and the latest reCAPTCHA is that this one hides everything from the user until necessary. Whereas Google's reCAPTCHA still requires the user to select a check box. Also when trying out both, Google's reCAPTCHA was unsure I was a real user a lot more than when using Ghost CAPTCHA. 

## Gamification
Games are a great UX in their own right. Gamification in UX is a great way to disguise tasks that need doing, which in this instance is verification. Why not turn verification into a game? [PlayThru is a playful alternative to authorisation] offering a game instead of distorted text. 

<div class="images">
	<img class="rounded portrait" src="/images/posts/security-verification/playthru.png" alt="sample of the game playthru offers instead of CAPTCHAs, like build a face">
</div>

Luckily for our users who use screen-readers, there is also an audio version of the games. But anyone on a braille display is going to struggle.  The game is friendly to users from different cultural backgrounds. Games like 'build a face' complete with moustache and mouth don’t *necessarily* need text for users to pick up on what to do. It is unfortunate though that it looks like you can't translate the text. Those who depend on keyboard only methods are also restricted by PlayThru, which is also something worth considering. 

Bots and Spam know no boundaries and this is a great way to add this layer of verification in a playful context. This is a great addition to sites aimed at children. It’s engaging and it doesn't break the flow too much or put off the child. This is also something they will want to do, rather than the parent and doesn't break the user journey up either.

Yet the problem again we have is the seriousness of this type of verification. It’s great for children sites, but actually not a lot of sites enforce registering. There are a lot of sites where this look and feel wouldn’t fit in well. If I had to sign in to my university account by playing a game, I wouldn’t take it so seriously. When one of the games is feeding a baby, it’s hard to ignore the childish element to it. 

## Email Address Verification
Asking for users to verify their address has its benefits, but at the same time we’re building in drop-off points into our user journey. Who wants to sign up, go into their email, click on a link, to go back to the site you just signed up on? If you’re lucky it will keep you logged in once verified. If not, you then have to go back to the home page to log in.

There are reasons to make a user go through these steps, albeit many. Yet there are alternatives which we can hide from our user. A tool provided by [Experian] provides a [real time email verification] with [minimal impact on UX]. There are technologies out there that allows you to do real-time verification. Again, this removes the burden from the user of a problem that really isn’t their concern. For those there are some [open source tools offering the same] service. 

From an accessibility point of view, this means that users aren't distracted and we remove a pain point in their journey. It’s less frustration than clicking on links to prove my online address is real. Sometimes this is in addition to our user just proving they’re human. Is email verification another loophole that we have to put our users through?

## Image Recognition
The first time I was faced with this I thought it was an absolute ridiculous security measure. Who ups their security by asking “Do you recognise this apple? Oh you do! Great, continue!” Really, an apple? 

However image recognition is not only verifying that you’re logging in to the correct account but it’s making sure you’re logging into the right place. This is more of a prevention for phishing websites and is smart way of providing a quick way to ensure the user realises what site they’re really on. 

Now the problem comes in when a user tries to logon and they’re faced with a random image code. On one bank the image you’re supposed to recognised is read out using a code for example “House and Home 59176”. Now for this bank, already [you have to remember another 3 numeric only passwords]. Do I have to now remember a code for an image too?

*Ain't nobody got time for that.*


## Security Questions
I’m sure we've all seen security questions before. Usually you associate them as an additional security layer when you've forgotten account credentials. They are arguably just as important and sensitive as passwords. If a user has forgotten their login credentials these are usually a first point of call of verification. But sites like United Utilities also uses security questions as part of the login. 

<div class="images">
	<img class="rounded landscape medium" src="/images/posts/security-verification/united-utilities.png" alt="Logging into United Utilities asks for a security question when logging in.">
</div>

*What’s worse is that this information is not even masked.*

One of the issues I find with security questions is that they ask for sensitive information. As more and [more information is being stored on us], whether we like it or not this data is becoming more and more insecure with the popularity of social networks on the increase.

| Question Example     											 | Found on      											  |
| ---------------------											 | ------------- 											  |
| What was the name of your elementary/primary school?      	 | **Facebook**, under education section 					  |
| What is the name of the place your wedding reception was held? | **Asked someone as small talk** (Tested on a colleague)    |
| In what town was your first job?								 | **Facebook**, under employment section 					  |

Of course you could ask something someone would never admit to, such as "Where did you lose your virginity?" or “What’s your most disgusting habit?”. But these questions don't seem to not invade your private life. With big data and social networks, there has never been more personal and private data on record. I mean, [people post what they have for tea] and [selfies on the loo].

*Privacy is becoming a fickle thing.*

The whole experience of security questions is not as safe and secure as we’d like to think. The answers are public knowledge for the most part and when users enter the information, it’s never masked. Users are now answering the questions with incorrect answers, but this has two problems. Firstly, users are now taking security into their own hands because of a lack of trust in what you’re requiring. Secondly, they now have to remember the wrong answer to your question.

*Is it now a test of whether or not it's you, or your memory?*

Even LastPass argues that your answers to your [security questions should be random as well], demonstrating this was how [Sarah Palin’s account was hacked].

## Honey Pots
Pesky bots are an issue, but whose issue is it really? What I don't understand is, actually, why are we passing on the problem of detecting bots to the user?

*Bots are not the user's problem.*

This is [not to be confused with a honey pot that is server-side].

Now with this approach, the fields have to be hidden contextually rather than just by the presentation. What I mean by this is hiding the fields in the HTML content, rather than hiding it with using CSS. 
<div class="code-and-icon">
	<pre><code>input type="hidden" value="" name="context"</code></pre><i class="fa fa-check green"></i>
</div>

rather than

<div class="code-and-icon">
	<pre><code>.hidden { visibility: hidden; } </code></pre><i class="fa fa-times red"></i>
</div>
<p>or</p>
<div class="code-and-icon">
	<pre><code>.hidden { opacity: 0.0; }</code></pre><i class="fa fa-times red"></i>
</div>
Logically, it makes more sense to hide it in the HTML, but we also hide it from screen-readers. This means a visually impaired user is not left confused by this mystery field being read out to them. If you take a look at Twitter’s login form, you can see how it’s done:

<div class="images">
	<img src="/images/posts/security-verification/twitter-one.png" alt="Code showing hidden in HTML input fields on Twitter" class="two medium">
	<img src="/images/posts/security-verification/twitter-two.png" alt="Showing the hidden fields on Twitter sign up form" class="two medium">
</div>

## Pre-Verified Sign-In
Pre-verified sign-in allows your users to register to your website using an existing account; like Google. [There is an on-going debate]  on whether single sign is a good or bad idea. An advantage to using it is that a third party handles verification meaning you don’t have to. This also means that in terms of passwords, your user only has to remember one password§ to an account that you don’t have to manage.

Unfortunately this means that you have to analyse which accounts your users use most and integrate those first. But if you go down the route like Flickr, your user might hit a brick wall. If users don’t have an account with the third parties you’re offering to integrate with, they can't continue. Why a website would only offer one option is beyond me, and Yahoo nonetheless. They even have [a page justifying their poor UX decisions]. They say it’s “one login to rule them all”, yet I have to create a Yahoo account, to create a Flickr account. This completely defeats the point. They also suggest linking your photos from Facebook and sharing them on a wider scale. If I wanted that, I would be posting them to Flickr, not Facebook. To me, this is a total turn off when signing up to a service.

<div class="images">
	<img src="/images/posts/security-verification/flickr.png" class="rounded landscape small" alt="Flickr demanding a login with a Yahoo account">
</div>

From a user’s perspective, they have one master account to rule them all. No verification step per new service they sign up to. One password to remember. That’s all great but the app permissions that an integrating app demands is ridiculous. If you use Google to sign into everything, that’s a lot of private data you’re allowing apps to access. Try and keep the permissions to a minimum, so as not to scare off your users. If you offer your users to join by using their Facebook account, they shouldn't have to hand over permissions, like posting on their behalf. It also shouldn't mean that they automatically endorse your brand and advertise it.

## In Summary
When a site gains more attention it becomes more of a target for hacking and bots. Usability often then gets traded in, for favour of security. 
With good usability comes a good amount of traffic.
At the end of the day that’s exactly what we want and that’s what our users want. Sometimes we have to make tough decisions when it comes to priority. Here we’ve looked at how some of those decisions don’t have to go from one extreme to the next and there’s a line in between. Remember:

1. Honeypots are a good way of hiding the issue from your users,
2. Always hide honey pots in the HTML not CSS,
3. Demand more from your captchas. If you’re going to use one, why not try [Ghost CAPTCHA]?
4. With security questions, comes great responsibility. Mask the answers and allow unmasking,
5. Add the ability to show a password when needed, especially on (but not limited to) handheld devices or tricky passwords like default WiFi.

But these measures should only be taken if  your site needs it. Before adding any of these options ask yourself why? Do you really need this layer of security? If so, that’s fine. As with most security measures, don’t forget to weigh each one up with usability. There’s also nothing stopping you using a combination. 

[spam reigns our Tumblr comments]:https://www.tumblr.com/docs/en/deal_with_spam
[computer has never passed the Turing test]:http://blogs.telegraph.co.uk/technology/jamiebartlett/100013858/no-eugene-didnt-pass-the-turing-test-but-he-will-soon/
[blogs like this CAPTCHA one]:http://www.usertesting.com/blog/2014/04/09/think-your-site-needs-captcha-try-these-user-friendly-alternatives/
[CAPTCHAs are little boxes with distorted text]:http://www.captcha.net/
[reCAPTCHAs]:https://www.google.com/recaptcha/intro/index.html
[helping decode books scanned]:http://techcrunch.com/2007/09/16/recaptcha-using-captchas-to-digitize-books/ 
[UK ranks low when it comes to numeracy skills amongst adults]:http://www.huffingtonpost.co.uk/2013/10/08/uk-young-people-skills-behind-world-oecd_n_4061741.html
[There are no stupid users, only stupid interfaces.]:http://ignorethecode.net/blog/2008/05/30/there-are-no-stupid-users-only-stupid-user-interface-designers/
[Quantum Random Bit Generator]:http://random.irb.hr/
[people post what they have for tea]:https://twitter.com/bladderbloat/status/625338608522776576
[selfies on the loo]:https://twitter.com/search?q=toilet%20selfies&src=typd
[security questions should be random as well]:https://blog.lastpass.com/2013/06/your-answers-to-security-questions-should-be-random-too.html/ 
[Sarah Palin’s account was hacked]:https://en.wikipedia.org/wiki/Sarah_Palin_email_hack 
[more information is being stored on us]:http://www.ibtimes.co.uk/apple-mac-os-x-yosemite-secretly-uploading-private-data-icloud-servers-1471901 
[you have to remember another 3 numeric only passwords]:http://echesters.co.uk/ux-security-passwords 
[CAPTCHAs]:http://www.captchacreator.com/v-examples.html?id=2# 
[accessible CAPTCHA]:http://www.afb.org/blog/afb-blog/can-captchas-be-made-accessible/12 
[There is an on-going debate]:http://www.zdnet.com/article/why-single-sign-on-is-not-a-good-idea/ 
[not to be confused with a honey pot that is server-side]:http://www.honeynet.org/node/158 
[Ghost CAPTCHA]:http://pjtops.com/app/GhostCaptcha/ 
[a page justifying their poor UX decisions]:https://help.yahoo.com/kb/flickr/SLN22740.html?impressions=true 
[American Foundation for the Blind]:http://www.afb.org/default.aspx 
[Experian]:www.edq.com/
[real time email verification]:https://www.edq.com/uk/products/email-validation/ 
[minimal impact on UX]:https://www.edq.com/blog/real-time-email-verification-with-minimal-impact-on-ux/ 
[open source tools offering the same]:https://opensourceenterprise.wordpress.com/2012/10/09/email-address-verification-on-mailbox-proof-of-concept/ 
[PlayThru is a playful alternative to authorisation]:http://blog.areyouahuman.com/help/english.html
[redesigned a new ReCAPTCHA concept]:https://www.google.com/recaptcha/intro/index.html#