---
layout: post
title: Learn HTML in one day – part one
categories: HTML
tags: [learn, html]
---

When i started thinking about making a web presence for myself, it was back in 2008. I was really into the world of internet that i used to spend 18 hours before my computer screen. Every moment was enjoyable. I was always eager to learn coding stuff. I’ve coded mIRC scripts, it was easy it took me 2 weeks and then I rocked it! So I thought, why not go to the next level; websites! And then everything changed.

I remeber the first book I read about HTML was in a .chm format. It was a horrible format as the ebook readers for such format were really ugly back then. But you know, I’ve read the whole book anyway. And guess what; I fell in love with web development. It’s been 8 years now and I’ve never enjoyed anything more than making website .. AKA writing HTML and CSS.

HTML is easy
<pre lang="no-highlight"><code>
&lt;!doctype html&gt;
&lt;html&gt;
&lt;head&gt;
&lt;meta chrset="utf-8"&gt;
&lt;link rel="stylesheet" href="style.css"&gt;
&lt;title&gt;I'm the title of the page&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;header&gt;I'm the header zone&lt;br&gt;
&lt;ul&gt;
&lt;li&gt;i'm a list item&lt;/li&gt;
&lt;li&gt;I'm another list item&lt;/li&gt;
&lt;/ul&gt;
&lt;/header&gt;
&lt;main&gt;I'm the main content zone
&lt;div&gt;I'm a block of content&lt;/div&gt;
&lt;p&gt;I'm a paragraph&lt;/p&gt;
&lt;a href="https://cesr.net"&gt;URL of a web development site&lt;/a&gt;
&lt;img src="http://lorempixel.com/400/200/"&gt;
&lt;/main&gt;
&lt;footer&gt;I'm the footer zone&lt;/footer&gt;
&lt;/body&gt;
&lt;/html&gt;
</code></pre>
Guess what, The few lines of code that you saw up there is almost all you need to know about HTML in order to write web pages. Yes, that’s it. But there’s a catch, I will not be leaving you at that basic level. After all, What Intend to teach you eventually is advanced level HTML, css and Javascript. Stay with me, and I’ll make a stunning web developer out of you. Bookmark the blog now; you will be visiting it more often throught your journey of becoming a neat developer.

You probably don’t know this, or maybe you do, but the thing everyone that have been involved in some sort of coding knows, is that HTML could be the easiest language on earth. It’s a markup language used to structure content. You can be a guru within a day or a few days depending on your enthusiasm to learn and the free time you have.

Making your HTML page Real

Most web browsers will identify your HTML page if you just name it with the suffix (extension) .HTML but if you want to write correct, robust and real HTML pages, you will need to know how to identify the right wat to write those pages.

&lt;!doctype html&gt;

This line of code is self-explanatory. You want to start your page with it in order to tell the browser that this page is HTML. In the very beginninf of your page, you put the !DOCTYPE HTML between &lt; &gt;. You will see a lot of these in HTML. Ok so now we know that !DOCTYPE declarance is easy to remember, short and descriptive. Moving on.

&lt;meta chrset="utf-8"&gt;

This line of code tells the browser reading your page that your HTML is using a character set of UTF-8 which is a universal set of character encoding. It enables you to make even the strangest languages appear correctly and become readable. So for example if you have a page written in chinese, no problem, Browsers will display the alphabet correctly to the users.

&lt;title&gt;I'm the title of the page&lt;/title&gt;

Some people don’t notice that having a title on your page can make make the difference between making a valid web page and shooting yourself in the foot. It’s a fatal mistake and it even hurts your page’s popularity on the web. Unlike what some people might think; it’s not optional. You must include a title about the page!

HTML elements

Now we’re getting to the beef of the language. It’s delicious and easy to chew on as well. You can even bet your grandma understands this post; she will.

HTML has &lt;&gt; for all its elements.
HTML has some elements with opening tags &lt;&gt; and closing &lt;/&gt; tags
Content goes within those tags.
HTML element sometimes have attributes. They describe something about the element.
HTML has an element for its head, an element for its body, and an element for its foot.
HTML has elements placed inside other elements. Hence, they are considered children of their parent elements.
HTML has the convenience of allowing you to add comments within page code.
Lets discuss these points one by one, as they will greatly enhance our understanding of the language.

 

The home for HTML elements: &lt;&gt;

