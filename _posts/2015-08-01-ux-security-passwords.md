---
layout: post
title: Five ways of improving the UX and security of passwords
description: It seems like security and user experience are always in tension. Logging into my bank seems fraught with nothing but pain points, frustration and curiosity. Why is it one or the other when it comes to security and user experience?
---
It seems like security and user experience are always in tension. Logging into my bank seems fraught with nothing but pain points, frustration and curiosity. Why is it one or the other when it comes to security and user experience? Why, in a world where we have dozens of accounts for everything, have we not found an easier way to stay secure without compromising on usability?

Throughout this post I want to break down how some of the experiences around passwords suck and how we can make them suck just that little bit less.

## Passwords
Passwords are a security measure that to some extent is out of your hands. You can't choose a password for your user or offer on hand guidance during registration. One of the most common ways to compromise an account is through its password. So it's no wonder that passwords are a delicate topic when it comes to security and user experience. 

You can calculate the complexity of a password with this simplified formula:

<code>number_of_available_characters ^ length</code>

Based on this formula, increasing the length has much more impact than adding numbers or punctuation. For example if I was to brute force a password of **5** characters, there would be **4182119424** possibilities. Yet if I was to brute force a password with **7**, there would be **29509034655744** amount of possibilities. That's only a 2 character difference!

A password's strength also comes from its randomness. Randomness, in the context of a password, also refers to its relevance to the user. If my password consisted of my family's names like **"BobMaryJohn"**, its strength would decrease. Information like family or pet names is accessible online, making guessing passwords easier. This is the same for phrases with a theme like **"HarryRonHermione"**. Phrases with little relevance to itself and the user, like **"CarCherrySwimming"** create stronger passwords.

What I don't think works is having multiple passwords that are both enforced with similar rules and yet different names on different pages. I'm not kidding, this is the bank I refer to handles their security. Security digit, 5-digit number, ID, personal ID, customer ID, password were names of all the numbers I needed for my login details. Yet some of these refer to the same thing! Their rules were so strict regarding numbers and lack of alphabetic characters, I took to writing my passwords down. Remembering the nth, n+1th and n+4th digit of numberic only passwords is impractical and near on impossible for someone with a cognitive disability. 

After the third time of requesting new passwords and customer numbers and security digits and God knows what else from my bank, I had had enough. For months at a time I couldn't sign into my account. My flat mate who had the joint account with me didn't even bother and left the finances to me. Yes, I'll admit the bank is secure and I feel my finances are safe, but should my finances be safe from me? Probably, but that’s not my point.  

## Password rules
We get told passwords are 'good' when they follow rules a, b and c, and then elsewhere we get told rules x, y and z. Passwords are 'even better' when they're [unmemorable for humans] and are unique.

Password rules are a way of ensuring your users have decent passwords. Yet if you’re going to enforce rules, tell the user before entering and submitting a password. A few times I've faced with an “error” about a rule I haven’t complied with because I didn't even know about it. If it’s something I have to do to sign up to your service, why hide it from me and ‘blame’ me for the error?

*Show me the rules.*

I find the biggest problem with password rules is the inconsistency between websites. A good password is subjective in the first place and it seems no one can agree on the rules on [how to make a good password]. Opinions on how to make a good password not only seem to be forever changing but they're also [an ongoing debate].

Try and find a popular website which requires the same level of security that you need and use the same rules. If users find your rules to be too much they will find a way to make the situation suit themselves, as this comic demonstrates.

<div class="images">
<img class="portrait" src="/images/posts/secure-passwords.jpg" alt="A comic showing a man going through tough security procedures, scanning his finger prints, going through multiple vaults and safes to then shout his password out of the window to another man">
</div>

The language around password rules also sucks. The average person is unaware of the security risks an insecure password can cause. More than likely they don’t know what makes a password stronger. As far as they're concerned they haven't done something wrong. It's likely they've reentered their password that has been accepted on a different site.

*Explain why we're enforcing rules.*

Offering suggestive language such as: “A strong password consists of rules a, b and c” is a lot friendlier than “Enter a password with a,b,c”. The first approach is less of a dictatorship and is a teaching approach of what makes a good password. Even if you enforce rules, by offering a suggestive approach, it still feels like you have the user’s interests at heart. Users are more likely to take suggested good practices with them onto other sites.

## Password Strength Indicators
Death to password strength indicators. They are so judgmental, and they’re never consistent. On one website your password flashes green with “strong” underneath. This actually feels rewarding until you take your ‘ultra-secure’ password to another site, (yes this is bad practice but password managers is a whole new kettle of fish.) where it flashes amber with “medium” underneath. Medium. That password has every symbol in it under the sun!

*Don’t judge me for my passwords.*

If you go down the route of having password rules then any password matching those criteria, as far as the user is concerned is secure. No part of my experience adhering to the rules given to me by the application should then judge me for my choices. Essentially you got what you asked for. Technically "Hello2U!" meets strong password rules criteria, but as it contains a dictionary word it's easy to predict. While the password "H3ll02U!" may look stronger, [Leet Speak] is a common and predictable fallback, which is also easy to brute force.

## Passwords on Forms

### Password Confirmation

When asking for passwords, should you confirm a password and require the phrase to be entered twice? From personal experience, yes and this also goes for emails. I have created accounts to then not realize my information was incorrect, until I haven't received my verification emails. Due to my mistake I couldn't log in and had to start the process all over again. It's easy to make mistakes and they should be caught as early as possible throughout the process. Typos are so common, why not account for them?

There’s nothing worse than locking yourself out of your account before being able to use the site. It seems annoying asking twice, but people get around this by copy and paste, and it’s worth it in the long term. It prevents more “forgotten password” journeys before a user has had their account for 5 minutes. Yet if there is a mistake inside either of the password fields, a user can't see the issue. This leads to a form submission with mismatching passwords and both fields needing to be redone. There is nothing more frustrating.

### Unmask Password
Password unmasking and showing one letter at a time as you type is becoming more common. On devices like phones where it's tricky to type, this. The feature may not be something that seems obvious to offer, yet on devices where it's tricky to type, it eliminates asking for passwords twice. The ability to view password fields, allows your user to double check their password if they think they entered an incorrect phrase.

*Most of the time your users are typing in passwords in private.*

Providing feedback and visualising the system status are [basic usability principles]. [Masking users' input], including that of a password is not compliant with this principle. In fact, **unmasking passwords relieve the previous issue of asking for the password twice**. Why ask for repeated information, when we can check the original information? This means you're not duplicating the problem for those suffering with disabilities ad you're not duplicating effort for your users.

### Field Attributes
The use of password managers is a whole other kettle of fish. While I'm not religious about using mine I can see how this takes away a lot of the UX pain we've just discussed. Earlier we mentioned denying copy and paste functions on password fields. Unfortunately companies say they need to adhere to this rule for their security certification.

<div class="images">
	<a href="https://twitter.com/BritishGasHelp/status/463619139220021248"><img src="http://lh3.ggpht.com/-n70GcZpf5FM/U3R0EeH5EhI/AAAAAAAAGnk/Seh-_JYM8ww/image1%25255B1%25255D.png?imgmax=800" alt="A tweet saying: Disallowing pasting and therefore password managers is NOT a standard practice. It's unnecessary and dangerous"></a>
</div>

But onpaste is a key part of the journey using a password manager, especially on a phone. If you don't allow paste on your password field on your app then the user has to manually type in the passphrase. On a phone, flicking between screens is awful as well as remembering horrendous passwords. These passwords are horrendous for a reason! 

It's amazing how websites like PayPal and T-Mobile choose the UX [decision to disable the use of password managers]. PayPal, to me is a site attached to my finances, where a unique and unmemorable password is crucial. Disabling onpaste is disabling the use of password managers. Utter madness. 

<div class="images">
	<a href="https://twitter.com/waldojaquith/status/623599384664637440"><img src="/images/posts/t-mobile-onpaste.png" alt="Shows the onpaste being disabled on T-Mobile's website"></a>
</div>

In contrast I can understand why sites choose to disable the on-copy functionality. The browser auto-fill saves a lot of time and effort in saving details, although it does not store them and hide them inside the browser well. In Chrome your password isn't even requested when editing stored credit card details. This means it would be ridiculously quick and easy to copy someone's stored password from a field. But how often is someone else on your machine? ​On your personal machine it might not a big problem and on shared machines you can have separate accounts.

*When would you need to copy a password field?*

Granted, I've forgotten a password and I've needed to enter it on another device. I either go into my password manager to look up the list of saved passwords in my browser; or just manipulate the HTML to show the password. Even then I can't copy to clipboard and paste between devices. Allowing the oncopy function makes my password a more accessible piece of content which is the complete opposite of its purpose. As users move across devices, they expect a seamless transition from one to the other.

## In Summary
There is definite room for improvement for passwords when it comes to both security and user experience. But like a lot of security and UX topics they can be overwhelming with research, statistics and opinions with no clear answer at the end. 
When dealing with passwords remember a few golden rules:

* If you're going to enforce password rules, tell the user.
* Suggest why your password rules matter and why the user should adhere to them.
* Ditch the strength indicators. Please.
* Leave the onpaste alone! But destroy the oncopy function. 

[basic usability principles]:http://www.nngroup.com/articles/ten-usability-heuristics/
[unmemorable for humans]:https://imgs.xkcd.com/comics/password_strength.png
[how to make a good password]:http://uk.pcmag.com/software/29/news/youre-still-using-terrible-passwords 
[an ongoing debate]:http://www.theemailadmin.com/2012/09/length-versus-complexity-the-great-password-debate-rages-on/
[Leet Speak]:https://en.wikipedia.org/wiki/Leet 
[Masking users' input]:http://www.nngroup.com/articles/stop-password-masking/ 
[decision to disable the use of password managers]:http://www.wired.com/2015/07/websites-please-stop-blocking-password-managers-2015/ 
