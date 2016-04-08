---
layout: post
title: The UX of Flags
description: What does a flag actually represent? Where can they be helpful, and where are they a hindrance in UX?
---

Flags are amazing. They're these icons that everyone seems to know. They're used in games and are dotted about all over the place, no matter your culture. But there is more than what meets the eye with flags. When you first think of a flag, what do you picture? Your country’s flag? A flag for your leisure group? 

## What is a flag?
<strong>Flag:</strong>
<p class="emphasis">A piece of cloth or similar material, typically oblong or square, attachable by one edge to a pole or rope and used as the symbol or emblem of a country or institution or as a decoration during public festivities.</p>

A flag is also an icon and are used to represent so many things. Usually we’ll think of countries when we think of flags. Then when you head to Catalonia and ask for a Spanish flag, you’ll be quickly told that they have their own. So not only do countries have flags, so do their regions. 

<div class="images">
	<figure class="col-xs-12 col-sm-6">
     	<img class="same-height" src="/images/posts/flag-of-spain.png">
     	<figcaption>The Spanish flag</figcaption>
     </figure>
     <figure class="col-xs-12 col-sm-6">
     	<img class="same-height" src="/images/posts/flag-of-catalunya.png">
     	<figcaption>The Catalan flag</figcaption>
     </figure>
</div>

If you’ve ever watched Big Bang Theory you will have also learnt a few flag facts. How flags are used to surrender in battles and represent sides in battles. For example the confederate flag, and the Nazi battle flag. Anyone can make their own flag.

## The temptations
When you’re providing a list of languages where using a dropdown/button combination doesn’t make sense, flags are a visual temptation. For my first UX ever project we were faced with offering a list of 14 languages. For a small non-profit it was amazing to show their global reach and how accessible their petition forms were. Yet, since the number did not take kindly to being divided, we opted for this.

<strong>A World At School:</strong>
<div class="images">
	<img class="landscape" src="/images/posts/AWAS-languages.png" alt="A long list of languages in which A World at School offers their petition form">
</div>

Looking back it feels like a monstrosity. Even I would argue that that example was in desperate need of some visual love and care with flags. But with just 5 minutes of research of representing languages with flags, every thing said no.

## Languages
When even the London Underground has a flag, it’s hard to imagine why in the online world we associate flags with languages. Both languages and flags in their own right mean so much more. 

<div class="images col-xs-12">
	<img src="/images/posts/london-underground.jpg" class="col-xs-12 position central small" alt="London underground flag flying over St James's Park station">
</div>

The first issue with using flags for languages is that it is not a one-to-one relationship. A language is spoken in multiple countries, and a country can have multiple official languages. For example, in China they have 8 official languages. So if a user selected a Chinese flag, which language should they expect? Another example is English. Personally I consider English to be invasive, with words creeping into every language. But it is [an official language of many countries], from England and America, to India and the Philippines.

Using flags to represent languages is a confusing design choice for everyone for more reasons than you might think. Language can be very personal, and is a huge part of your culture. I cannot stand it when I am presented with a Brazilian flag when selecting my resource in Portuguese. It’s not where the language originated from. It’s also the same when an American flag is used for selecting English. Language should balance reflecting the company's identity with target audience. It can be disheartening to see a British company use American spelling.

> <i class="fa fa-quote-left"></i> I hate it when I get [X] flag for the [Y] language

If you have ever brought this up for discussion, you’ll probably have heard that. You don’t want to be inducing hatred in your designs. Quite often the language selection comes very early on in your user journey. From there it doesn't set the right tone from the beginning.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">I am OUTRAGED at these silly new <a href="https://twitter.com/OxfordWords">@OxfordWords</a>! Wasn&#39;t the laugh-till-you-cry emoji enough? <a href="https://t.co/saSrhCuQaF">https://t.co/saSrhCuQaF</a></p>&mdash; Mary Norris (@MaryNorrisTNY) <a href="https://twitter.com/MaryNorrisTNY/status/715877188868833280">April 1, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

Flags are also personal. Groups burning another group’s flag is often used in media to show extremism. 

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Flag just burned outside 4th precinct by small group, others in crowd condemning <a href="https://t.co/idew2ZScyk">pic.twitter.com/idew2ZScyk</a></p>&mdash; bengarvin (@bengarvin) <a href="https://twitter.com/bengarvin/status/715377336107950080">March 31, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

So depending on your target audience, it would be wrong to assume that your user knows their flag. The best suggestion to offering language selection is providing a list of languages, in both Latin and the original script. 

#### Why use Latin script in addition?

The best subtitles for videos in scripts similar to Farsi and Urdu offer 3 subtitles.

<div class="subtitles">
	<p lang="fa" dir="rtl">مین ایک نستعلیق سبٹیٹل  ہن</p>
	<p>mfan afake nst‘lfaq sbtfatl hen</p>
	<p>I am a Nastaliq subtitle</p>
</div>

<img src="/images/posts/Coke Studio - subtitle.png" class="col-xs-12" alt="Screenshot of YouTube video from Coke Studios with 3 types of subtitles">

The first subtitle is for those who are native and can understand and read the script. The second is for those who can understand the language, but not necessarily the script. These are usually the younger generation who have family from there, but live in a country where learning the script is not as easy. The third subtitle is translating the video to a broader audience who can read English.

<p class="emphasis">Now that is accessibility.</p>

## Countries
If using flags for languages doesn’t make sense, surely it does when offering preferences for a user to select their country? Not necessarily. An issue that’s frequently caught during usability tests with flags is that users struggle to quickly identify if it’s asking for a location or for a language preference. You’re then faced with a German speaker located in England hitting the UK flag. Flags for countries when choosing delivery addresses or location based products makes sense. But selecting a flag to choose a location should not restrict anyone from changing their language. 

### Delivery Address
A site that was sent my way recently was Harrod’s. The way that Harrod’s uses flags is by offering a list of countries with each flag when selecting a delivery address. This is helpful and allows for quicker selection. A vibrant flag is much quicker to spot than your country from a list of words that look the same. Users don’t have to read first or as carefully, leading to an effortless experience. 

<img src="/images/posts/harrods-delivery-country.png" alt="Screenshot of Harrod's delivery country list with flags">

This is in contrast to the completely separate approach that Amazon has. Instead of choosing your language, currency or country, everything depends on which site you’re on. For example, there is an amazon.co.uk, and an amazon.de. What I find interesting is that is doesn’t detect your location and doesn’t offer an alternative link. But for some reason detecting a location and offering another website is for some reason common among cooking websites!

<img src="/images/posts/food-network.png" class="col-xs-12">

## Currencies
At first thought, you expect currencies to be a 1 to 1 relationship with a country. This then leads to the temptation of using a flag for a currency. Flags are certainly more eye-catching than a country’s currency symbol and if used can lead to a faster selection. But without the extreme example of [Zimbabwe’s current currency crisis], countries still don’t always have such a simple relationship. Countries choose to keep their savings in a foreign currency which is more stable than theirs. For example in Ukraine, you can make large payments in US Dollars or in Euros. Those currencies are more stable than their official currency, the Hryvnia. 

Most of the companies I buy from, I don’t have to choose which currency to trade in. Yet for higher-end shops, such as Harrod’s, where their target market is global, this is something that’s worth putting thought into. ​In these situations​, their target audience have a tendency of trading in multiple currencies. Setting the delivery country doesn’t guess your preferred currency or add in any other location settings. Yet when you're on Amazon.co.uk it's more of a given that you want to pay in British Pounds. This is where users should not have to explicitly set their currency preferences.

<img src="/images/posts/harrods-currency.png" alt="Screenshot of how flags are only used for delivery countries and not the currency, but uses the symbols instead" class="col-xs-12">

## Phone Numbers
Another  scenario ​in which you can use flags is showing international dialling codes. The first digit is shared among regions, but every country has its own code, ​which is in the second digit. For example both the UK and Germany are in the +4 European dialling range, yet the UK is +44 and Germany is +49. For those interested here is [a list of each country and their area codes] and how this works. Unlike currencies, phone numbers don’t have their own symbol which is smaller and faster to pick out from a long list. Using a flag with a phone number, allows for something more scannable than a list of numbers.

<div class="images">
	<figure>
     	<img class="col-xs-12 same-height" src="/images/posts/amazon-phone-list.png">
     	<figcaption>Amazon's phone list</figcaption>
     </figure>
     <figure>
     	<img class="col-xs-12 same-height" src="/images/posts/ebay-phone-list.png">
     	<figcaption>Ebay's phone list</figcaption>
     </figure>
</div>

## In Summary

> <i class="fa fa-quote-left"></i> Sometimes I bring up the topic of flags and people are like “I don’t care about flags”. Trust me, 100% of people care about flags. There’s just something about them that works on our emotions. - Roman Mars, [TED Talk]

Flags mean a lot more to people than initially thought. It’s mindful to take a step back, realise what they actually mean and what they can be used to help with. Always analyse the relationship between the flag and what you’re using it for. Flags and an international dialling number is a 1 to 1 relationship, where as a flag and a language is many to many.

Even with the examples offered on where to use flags, be mindful that flags don't appear next to everything at the same time. It's confusing and it forces the user to double take on what preference or setting they’re making. Only use the flag in one scenario at a time for the page. Only use the flag in one scenario at a time ​on​ the page.


[an official language of many countries]:https://en.wikipedia.org/wiki/List_of_territorial_entities_where_English_is_an_official_language
[Zimbabwe’s current currency crisis]:http://www.bbc.co.uk/news/world-africa-26034078
[a list of each country and their area codes]:https://en.wikipedia.org/wiki/List_of_country_calling_codes
[TED Talk]:https://www.youtube.com/watch?v=pnv5iKB2hl4
