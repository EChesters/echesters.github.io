---
layout: post
title: How does language change across cultures - The Budaya Series 
description: The budaya series is articles exploring what consistently changes across cultures and how this impacts our UX. Here, we start with language. Where it's more than just words that changes.
image: "/images/posts/budaya.jpg"
---

The first concern when we go through a localisation project is the language of the next culture. Other than aesthetics, language is the first thing we judge something by. Google will let you know if the site is in another language and will offer to translate the page right at the top. Even in England for example, according to the BBC, in [London alone there are over 300 languages spoken]. You cannot guarantee that your primary users can speak the language you've chosen.

Language is also the first topic to look into across cultures because it’s not just words that change. Some [languages are renowned to have long words], like Dutch and German. This means layouts need to accommodate for the extra characters. Besides, not everything can be translated. A lot of the time context gets lost in translation, and meaning goes missing.

One thing to bear in mind with language is that it is so personal. I have struggled not knowing Portuguese when speaking to my family. As someone who has been trying to learn European Portuguese, it’s frustrating that resources are only in Brazilian. Who knows what I sound like when communicating with my family? I probably have some weird accent and I do get corrected on odd words.

There’s nothing more frustrating on holiday when you have the words. You know exactly what you want to say. But you can’t. It’s the same when it comes to reading or using a service. You’re not stupid. Neither are your users and unfortunately language is one of the biggest obstacles. It shouldn’t be a decision taken lightly.
[Language is also difficult to represent]. None of us are strangers to seeing languages represented by a flag. But what happens if I click the Chinese flag? They have 8 official languages! The best way is to simply list each language in its own language.

English
<p lang="es">Español</p>
<p lang="ru">Русский</p>

## High Context or Low Context

The differences between [the context types of cultures] can have a huge impact on designs. In [higher context cultures], feelings are more important than just being faced with facts. Whereas in low context cultures like English, they place priority on words and individualism, rather than aesthetics.

<div class="images">
	<figure class="col-xs-12">
     	<img src="/images/posts/budaya/language/KFC-en.png">
     	<figcaption>The English KFC website</figcaption>
     </figure>
</div>

As we can see here, it’s has a strong use of imagery and the words are quite minimal. The language used is aimed at the individual. It concentrates on being quite direct in solving your hunger problem, or money matters.

> <i class="fa fa-quote-left"></i> You better come twice as hungry

> <i class="fa fa-quote-left"></i> [...] for just £15

The Chinese version of the website is different, as we see below. The use of people with positive emotions is prominent. The colours are a lot brighter, with blues, greens, pinks and oranges, as opposed to the dark reds and browns on the UK version. “Wow” is repeated multiple times across the sections, and even on the packaging! There are a lot more options than low context cultures, with the nav bar having two rows.

<div class="images">
	<figure class="col-xs-12">
     	<img src="/images/posts/budaya/language/KFC-cn.png">
     	<figcaption>The Chinese KFC website</figcaption>
     </figure>
</div>

Location can also have an impact on how a high or low context culture presents itself. France has a high context culture. Harry Potter for example had an extra 1000 words once translated from English. Yet French websites have more in common with European low context cultures, than with Asian countries with a high context.

<div class="images">
	<figure class="col-xs-12">
     	<img src="/images/posts/budaya/language/KFC-fr.png">
     	<figcaption>The French KFC website is completely flash based, with automatic audio and a video background. It’s a lot busier than the UK site, but not as busy as its Asian version.
		</figcaption>
    </figure>
</div>

The way that information is presented varies between the two. Lower context cultures need a more explicit approach in explanations. Words alone have much less meaning and significance than those from higher context languages.

While Asian websites do tend to be busier, it is a misconception that they’re cluttered. Due to characteristics like the lack of punctuation, it can easily be misunderstood. For those who don’t understand, it’s hard to see what it’s saying and the page structure.

A clear example of this is the New York Times. They have almost the same layout for their English and Chinese versions. While both sites are content heavy the Chinese website looks more cluttered. Yet if you were to use the Chinese layout and change the text to be Latin based, it would look a lot less cluttered.

<div class="images">
	<figure class="col-xs-12 col-sm-6">
     	<img class="same-height" src="/images/posts/budaya/language/new-york-times-cn.png">
     	<figcaption>The Chinese website for The New York Times</figcaption>
     </figure>
     <figure class="col-xs-12 col-sm-6">
     	<img class="same-height" src="/images/posts/budaya/language/new-york-times-en.png">
     	<figcaption>The English version of The New York Times website</figcaption>
     </figure>
</div>

## Grammar

When you provide content in languages that you may not be familiar with, it’s still a good idea to make sure you do some research yourself. Even if it’s just a few basic language rules. Common mistakes are often found in shorter messages. Mistakes usually being with capitalisation, like in German where they have capitalised nouns.

_Ich habe ein Hund_ — I have a dog in German. Note ‘dog’ is capitalised.

As well as grammar, you also have punctuation and special characters. Punctuation symbols and rules often change. For example in Spanish, they use the same [exclamation mark] and [question mark] as most Latin based languages. Yet they are at the end and the beginning of a sentence. In French they also have their own quote marks, and use double chevrons instead.

<p><span lang="es" class="emphasis">¡Ojo!</span> — Spanish exclamation (Look out!)</p>

<p><span lang="fr" class="emphasis">«Je suis une citation»</span> — French quotation marks</p>

Despite there being numerous charsets for different languages, UTF-8 is recommended as it includes support for every language. To ensure your page is using the charset, simply add the following line to the head section of your HTML.

*HTML 5:*
`<meta charset="utf-8">`

A single word in a lower context language has a lot less meaning and may demand more from things like error messages in your UI. Context in higher context cultures provides meaning without you having to be explicit. This is why in languages like Portuguese and Spanish, you can omit certain pronouns.

<div class="table-responsive col-xs-12 col-md-7 position central">
	<table class="table table-striped table-hover">
		<thead class="green">
			<tr><th class="text-center" colspan="2">Verb conjugations - ter/to have</th></tr>
			<tr>
				<th>English</th>
				<th>Portuguese</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>I have</td>
				<td>(eu) Tenho</td>
			</tr>
			<tr>
				<td>You have - singular</td>
				<td>(tu) Tens</td>
			</tr>
			<tr>
				<td>He/She/It has</td>
				<td>(ele/ela) Tem</td>
			</tr>
			<tr>
				<td>We have</td>
				<td>(nós) Temos</td>
			</tr>
			<tr>
				<td>You have - plural</td>
				<td>(vós) Tendes</td>
			</tr>
			<tr>
				<td>They have</td>
				<td>(eles/elas) Têm</td>
			</tr>
		</tbody>
	</table>
</div>

## Characteristics

We know that no two languages are the same, and that it’s not only the words that change but what else changes? It’s good to know the characteristics of a language especially when planning a layout. Characteristics such as **length**, **direction**, **character set** and **size** can differ.

Dutch is a longer language in comparison to English. This means the layout needs to be accommodating.

For languages such as Arabic, not only is the script different, but they read from right to left. When designing a layout, note that everything flips with the text. Navigation usually found on the left for Latin languages now moves to the right, along with the logo and primary buttons. Here is the McDonald’s website as an example in both English and Arabic.

<div class="images">
	<figure class="col-xs-12">
     	<img src="/images/posts/budaya/language/mcdonalds-english.png">
     	<figcaption>English McDonald’s website with navigation and logo on the left
		</figcaption>
     </figure>
     <figure class="col-xs-12">
     	<img src="/images/posts/budaya/language/mcdonalds-arab.png">
     	<figcaption>The Arabic McDonald’s website with navigation and logo on the right
		</figcaption>
     </figure>
</div>

Another characteristic of language is how they story tell. So this is less to do with structure, but how they emphasise. In sensitive situations on websites, in English it is easy to tell a story using typography techniques. The English language can emphasise in many ways using capital letters or Italics. In Japanese, they don’t have those capabilities. This can be a challenge for international websites that heavily rely on those aesthetics.

---

*The Budaya series aim to provide both user experiencers and developers with a template of what needs to be considered when taking your brand across cultures. With code snippets and real world design examples, here explores the differences from top to bottom, from all around the globe addressing why this is important for your product.*

[Language is also difficult to represent]:/2016/04/08/ux-of-flags.html
[London alone there are over 300 languages spoken]:http://www.bbc.co.uk/languages/european_languages/definitions.shtml
[languages are renowned to have long words]:http://www.ravi.io/language-word-lengths
[the context types of cultures]:https://en.wikipedia.org/wiki/High-_and_low-context_cultures
[higher context cultures]:http://blog.bitmarketing.com/website-design-cultural-differences-12.html
[exclamation mark]:https://en.wikipedia.org/wiki/Exclamation_mark
[question mark]:https://en.wikipedia.org/wiki/Quotation_mark