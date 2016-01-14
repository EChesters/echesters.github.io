---
layout: post
title: Cultural Accessibility
description: Accessibility is more than just disabilities, it's the actual accessing of data. So why when we talk about accessibility do we exclude those with different cultural expectations to our own?
---

Accessibility is all about accessing everyday objects such as buildings, information and technology, but how many of us consider the role that cultures plays in the accessibility of our designs? Culture adds filters to each one of us depending on where we were born and raised. Filters such as language and traditions can have a huge impact on how we access different types of information and the way in which we expect information to be presented. Throughout this article I will discuss some misconceptions about common subjects that differ from culture to culture that can wreak havoc if ignored.

## Names
There are a lot of [misconceptions about names] which programmers build into their systems. Names aren’t expected to have numbers, symbols or that they have a certain number of names in a specific order. Traditions around names changes, from country restrictions of names, where names originate from, to the order in which names are presented. In the South of India it is not common to have a second name, so when fields asking for surnames are set as required, people are forced to use alternatives, usually their fathers’ names, occupations or the village they come from. In a lot of countries like Romania and China, the name order changes with the family name given first, more-so on formal occasions like exams or when providing personal data online.

When approaching supporting names on a field you need to really narrow down what exactly you are doing with names and how much you need accurate data. For example if you are a bank you need accurate data for legal purposes. However for something as simple as Facebook how important is accuracy for a social network? As the audience is so broad, it doesn't make sense to have heavy validation on the name field. Depending on your type of application you can craft your validations to fit your needs. Another UX issue comes in when we limit text fields for where we expect a full given name. People from Latin countries have rather long names, so when presented with a credit card payment screen with a limited number of characters for the name field, it’s impossible to fit in their full name. This in turn means the name on the field doesn’t match that on the card and prevents people from paying for items online. Not only is this frustrating, but this means your client is losing money.

## Language
Language is one of the biggest ways we associate ourselves with a culture. It’s so personal and yet so public at the same time. Take China for example, they have 8 official languages, including Cantonese, Mandarin and even Portuguese. Taking history into account and researching into the languages that are actually spoken in the areas you are trying to target, you soon realise there are more than you originally thought. In Europe most English native speakers have the attitude that “most people speak English”. Despite 38% of people in the EU being able to speak English at a conversational level, actually 18% of Europe speaks German as their mother tongue, with only 16% of people speaking English as their mother tongue, which is the same percentage as those speaking Italian.

The languages you choose for your application depends on what the software aims to do. If it is aimed at those in medicine or law then this type of information needs to be presented in a user’s own language. The type of language used can already be difficult to understand, so in something as important as medicine are misunderstandings worth it?

## Location
Another strong influence on language in a country is its geographical location. Turkey’s only official language is Turkish with around 90% of its population speaking it. However looking at Turkey’s geographical location means that it’s a popular destination for refugees and immigrants coming in from the Middle East, increasing the number of languages spoken there tenfold. Australia’s location also has a huge impact on accessibility. For a country which is big enough to house Europe with room to spare, the population only comes to around 23.6 million. In comparison to the UK’s population of 64.1 million, this means there is a limited demand when it comes to certain industries in Australia. Language can be a huge influence on your brand and with such  a small population in the first place and a huge attraction for immigrants from Southeast Asia, can your brand afford to not offer information in as many languages as possible?

## Measurements
A big confusion on a daily basis is measurements, so much so that the UK have now decided to convert their [road signs to include both imperial and metric measurements]. The UK’s consistency with measurements alone can be inaccessible, with petrol being sold in quantities of litres but distance is calculated in miles per hour. These issues have been known to cause a lot of issues and not just in software, with a lot of [lorry drivers getting stuck under bridges] after misjudgements. Another similar event was in 1998 when NASA lost connection with the Mars Climate Orbiter due to confusion between the measurements that were being used. Back in 1983 when Canada was officially changing to use the metric system, half way during a flight [a plane ran out of fuel] as both the ground and plane crew had forgotten the recent measurement change and has miscalculated the plane to have around 20,400 kilos of fuel on board, when in fact they had just 9,144 kilos.

The key factor here to solving this issue as with most problems is communication within the team. Knowing early on which measurements you are supporting can help keep development on focus and consistency throughout the project. Narrowing down which measurements to use also comes from research of what your app is doing and knowing where it’s going to be used.

## Dates
Anyone who has had the one-in-a-lifetime experience of creating a system with [support for time zones] will know just how important accessibility is in this area. But time zones are not the only time related difference between cultures. The majority of the world go by the Gregorian calendar, with only a few countries choosing the lunar calendar. Saudi Arabia officially go by the lunar calendar, with websites offering flight and hotel dates by this calendar. Without knowing this you would have no idea (on Gregorian time) when you’ve actually booked your holiday. This means important yearly events like New Year aren’t when you expect.

The lunar calendar is also different in respect to how they work out their dates. Chinese New Year is never on the same date every year. Instead people wait for officials to tell them when events are, such as their New Year, which is similar to how Easter is celebrated each year in the Western world. When the majority of the world runs by the Gregorian country it’s hard to feel like it’s justified building support for the lunar calendar. However if you are building support for countries like Saudi Arabia or China, then these are things you will have to consider.

## Overall
Researching different cultures can be frustrating and fascinating at the same time. Despite cultures having their differences you can sometimes find common ground for your implementations. The Internet is a worldwide network, making information accessible from all over the world and these differences should be celebrated and embraced. It’s a fine balance between having to cater for everyone in the world and having simple workarounds to make things work for yourself as a user.

-----

If there are any cultural differences that you know of or have experienced, please tweet me at [@EChesters]!

[@echesters]:https://twitter.com/EChesters
[support for time zones]:https://www.youtube.com/watch?v=-5wpm-gesOY
[a plane ran out of fuel]:http://www.todayifoundout.com/index.php/2014/05/time-commercial-aircraft-ran-fuel-mid-flight-gimli-glider/
[lory drivers getting stuck under bridges]:http://cars.aol.co.uk/2013/04/25/stuck-truck-lorry-driver-jams-hgv-under-bridge/
[road signs to include both imperial and metric measurements]:http://www.bbc.co.uk/news/uk-29965935
[misconceptions about names]:http://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/