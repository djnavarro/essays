---
output: hugodown::md_document
title: "In between"
type: "post"
summary: "An essay I wrote back in 2019 about transitions of various kinds"
author: "Danielle Navarro"
tags: []
date: 2021-04-29
rmd_hash: dced5bd2165c1215

---

**\[NOTE\]**: This is not a new post. The original publication date was 2019-02-16. I've made minor edits to fix broken links and update the code to accommodate package updates (or comment on the failures to make the old code work), but the main text of the piece is otherwise unchanged. The footnotes are new additions that reflect how my perspective has changed in the two years since I wrote this.

Prelude. We're all in this together
-----------------------------------

The balancing act of being feminine but not too feminine, assertive but not aggressive, to hide one's anger, to work around the inconveniences imposed by men, these are things that every woman has to manage. As a transgender woman I feel this much as a cisgender woman does, but I am less experienced at managing this tension than they are, and it is a pressure that does not vanish in the company of women. The need to perform a suitable model of modern womanhood for cisgender women is a thing I feel acutely, and woe betide the trans woman who places a single foot wrongly in the presence of a particular kind of feminist.

There's a nice [article](https://s3.amazonaws.com/academia.edu.documents/33192453/Rachel_McKinnon_-_Forthcoming_-_Stereotype_threat_and_attributional_ambiguity_for_trans_women.pdf?AWSAccessKeyId=AKIAIWOWYYGZ2Y53UL3A&Expires=1549756967&Signature=t2DwqmBw%2FUBknppTOoUwfDs8dBQ%3D&response-content-disposition=inline%3B%20filename%3DStereotype_Threat_and_Attributional_Ambi.pdf) by Rachel Mackinnon discussing a few of the ways in which trans women are subject to sterotype threat and attributional ambiguity in contexts that a cisgender woman would never detect threats, never see danger coming. Whether in bathrooms or in meetings, in conversations at work or in finding a swimsuit, I find myself seeing trouble coming in situations that cis women breeze through with a fluent ease that I admire and envy.

I was thinking about all this when starting a training program intended for professional and academic women judged to have leadership potential within the University. The session opens with a Ben Lee song [*We're All In This Together*](https://www.youtube.com/watch?v=mTeZcHWHeW4), presumably intended to get everyone to stop, focus, and maybe think about what they really mean by the word "leadership". It's a nice method, playing into ideas of shared community and -- because the facilitator is a woman working with a room of women -- the shared bonds of being women in a world that isn't friendly to women (and that's all I'll say on the program besides how awesome it is)[^1] But as a transgender woman who has presumably displaced a cisgender woman in order to make it into this room, the line that pops out to me is

> I know you think about <br> Jumping ship before it sinks, <br> But we are all in this together. <br>

and I wonder, *but are we really*? Am I a part of this community? Do I deserve to be here? Quite apart from the question of whether I have earned the right to consider myself a leader, I also wonder whether I have earned the right to [consider myself a woman](/post/trans-women-are/).

I ponder this question any time I am in a space traditionally reserved for cisgender women. Do I belong? Should I be here? How many people in the room secretly think I do not deserve to be here, or would do if they knew what I am? When I read books on professional development that tell me that I cannot realise my potential if I don't bring my full self into the room, I wonder how I am supposed to do that?

Maybe I should jump ship before I sink.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='kr'><a href='https://rdrr.io/r/base/library.html'>library</a></span><span class='o'>(</span><span class='nv'>fontr</span><span class='o'>)</span>
<span class='kr'><a href='https://rdrr.io/r/base/library.html'>library</a></span><span class='o'>(</span><span class='nv'><a href='https://github.com/thomasp85/transformr'>transformr</a></span><span class='o'>)</span>
<span class='kr'><a href='https://rdrr.io/r/base/library.html'>library</a></span><span class='o'>(</span><span class='nv'><a href='https://github.com/yixuan/showtext'>showtext</a></span><span class='o'>)</span>
<span class='kr'><a href='https://rdrr.io/r/base/library.html'>library</a></span><span class='o'>(</span><span class='nv'><a href='http://tidyverse.tidyverse.org'>tidyverse</a></span><span class='o'>)</span>
<span class='kr'><a href='https://rdrr.io/r/base/library.html'>library</a></span><span class='o'>(</span><span class='nv'><a href='https://gganimate.com'>gganimate</a></span><span class='o'>)</span>
<span class='kr'><a href='https://rdrr.io/r/base/library.html'>library</a></span><span class='o'>(</span><span class='nv'><a href='https://github.com/thomasp85/tweenr'>tweenr</a></span><span class='o'>)</span>
<span class='kr'><a href='https://rdrr.io/r/base/library.html'>library</a></span><span class='o'>(</span><span class='nv'><a href='https://github.com/mdsumner/ggpolypath'>ggpolypath</a></span><span class='o'>)</span></code></pre>

</div>

<div class="highlight">

</div>

<br>

X. The Good Tran
----------------

> I'm afraid there's a tendency among some philosophers to suppose that philosophical investigations into race, gender, disability, trans issues, and so forth are no different methodologically from investigations into the question whether tables really exist. One difference, however, is that while tables aren't part of the philosophical conversation, trans people, disabled people, people of color, *are* part of the conversation. Or at least, we think we are. We're here. In the room. And we've suffered from life-long abuse. I've helped a friend die of AIDS, fending off the nurses who misgendered her, watching in horror as the priest invalidated her entire life at her funeral by reducing her to a man. I've been personally assaulted in public to prove that I was a man. I've had a friend trans-bashed. And as this beating was gang-related, she then lost her home. I've had a friend stripped by police-officers, forced to parade back and forth while they ridiculed and harassed her. So please understand that this is a little bit personal. <br>
>
> -- Talia Mae Bettcher, [*When Tables Speak*](http://dailynous.com/2018/05/30/tables-speak-existence-trans-philosophy-guest-talia-mae-bettcher/)

I appear to have been assigned the role of *The Good Tran*. It wasn't a choice I made, and I fear I lack the temperament to play my part. If life were a play, the casting call for The Good Tran would request a white, cis-passing middle class trans woman living quietly with her family. The Good Tran is not an activist. She plays out the proper feminine gender performance just as it is expected of cisgender women. Perhaps she holds feminist beliefs, perhaps she holds views on transgender rights, but she keeps them to herself, and does not seek the public eye *as* a trans woman. Maybe by accident she has accrued such a profile, but she remains modest, humble and kind. She will never place herself above a cisgender person (man or woman), but she will tell the inspiring story of her journey from a dark place to her blossoming as a trans woman, whereupon she will fade away. Above all else, she is not The Crazy Tranny.

My casting in this role stems from a few factors besides the demographic factors listed above. Perhaps most prominent is that, well, I rather wish I *were* The Good Tran. She seems level-headed, reasonable and kind, and whether it is a good thing or not I do want to be like her. But there are other factors in play. I am the right age for the role -- at 41 I am on the cusp of middle age -- I am a scientist of modest reputation, and I am in a position of seniority that I am eligible for inclusion in "Women in Leadership" professional development programs. All modesty aside, I do indeed have the potential to be a role model.

Yet as Talia Mae Bettcher notes in her very excellent essay *When Tables Speak*, I do not come to this role as a blank slate. Having stayed hidden most of my life, to the detriment of my mental health, and being somewhat early in transition despite my age, I do not find it easy to hide my anger or [my disorientation](/post/52-pickup). I'd *like* to be better at "just having a discussion" about [transgender topics](/post/nevertheless-she-desisted/) as if my experiences with being trans were no different to my experiences with being Bayesian, but I am not. There are too many old wounds that have never really healed, too many repressed fears that have not resoved. Despite my best laid plans, I often lash out emotionally (thereby revealing myself as The Crazy Tranny) when I'd prefer not to.

I'm still learning how best to control that.

> I've been hurt deeply. <br> I imagine I will heal one day. <br> But for now, we need a plan. <br>
>
> -- Alicia Florrick, *The Good Wife*

<br>

One. Thank you
--------------

The last time one of these "trans debates" went badly on Twitter, I deleted my history on the site and unwillingly withdrew for a few weeks out of fear of harassment. When it happened, though, there were so very many people kind enough to reach out to me with messages of support, and I wanted to find a way to express how grateful I felt for the kindness of strangers.

It hasn't been easy learning to be myself, and I often sometimes caught between feeling like a middle aged woman and a teenage girl. It's a very strange kind of *in-between* space to be in, and I don't always handle it well. As a way of expressing my gratitude I made a gif to share my gratitude.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='c'># use showfont to load the font</span>
<span class='nf'>font_add_google</span><span class='o'>(</span><span class='s'>"Allura"</span><span class='o'>)</span>

<span class='c'># use fontr to extract letter forms</span>
<span class='nv'>get_letter</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='nv'>ch</span>, <span class='nv'>xshift</span>, <span class='nv'>yshift</span>, <span class='nv'>id</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nv'>char_poly</span> <span class='o'>&lt;-</span>  <span class='nf'><a href='https://rdrr.io/pkg/fontr/man/glyph_polygon.html'>glyph_polygon</a></span><span class='o'>(</span>
    <span class='nv'>ch</span>, family <span class='o'>=</span> <span class='s'>"Allura"</span>, 
    face <span class='o'>=</span> <span class='s'>"regular"</span>, nseg <span class='o'>=</span> <span class='m'>20</span><span class='o'>)</span>
  <span class='nv'>char_poly</span><span class='o'>$</span><span class='nv'>x</span> <span class='o'>&lt;-</span> <span class='o'>(</span><span class='nv'>char_poly</span><span class='o'>$</span><span class='nv'>x</span> <span class='o'>*</span> <span class='m'>1.9</span><span class='o'>)</span> <span class='o'>+</span> <span class='nv'>xshift</span>
  <span class='nv'>char_poly</span><span class='o'>$</span><span class='nv'>y</span> <span class='o'>&lt;-</span> <span class='o'>(</span><span class='nv'>char_poly</span><span class='o'>$</span><span class='nv'>y</span> <span class='o'>*</span> <span class='m'>1.9</span><span class='o'>)</span> <span class='o'>+</span> <span class='nv'>yshift</span>
  <span class='nv'>char_poly</span><span class='o'>$</span><span class='nv'>id</span> <span class='o'>&lt;-</span> <span class='nv'>id</span>
  <span class='kr'><a href='https://rdrr.io/r/base/function.html'>return</a></span><span class='o'>(</span><span class='nv'>char_poly</span><span class='o'>)</span>
<span class='o'>&#125;</span>

<span class='c'># use transformr to add stars</span>
<span class='nv'>get_shape</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='nv'>xshift</span>, <span class='nv'>yshift</span>, <span class='nv'>id</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nv'>shape_poly</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/pkg/transformr/man/simple_shapes.html'>poly_star</a></span><span class='o'>(</span><span class='o'>)</span>
  <span class='nv'>shape_poly</span><span class='o'>$</span><span class='nv'>y</span> <span class='o'>&lt;-</span> <span class='o'>(</span><span class='o'>(</span><span class='nv'>shape_poly</span><span class='o'>$</span><span class='nv'>y</span> <span class='o'>+</span> <span class='m'>1</span><span class='o'>)</span> <span class='o'>/</span> <span class='m'>2.5</span><span class='o'>)</span> <span class='o'>+</span> <span class='nv'>yshift</span>
  <span class='nv'>shape_poly</span><span class='o'>$</span><span class='nv'>x</span> <span class='o'>&lt;-</span> <span class='o'>(</span><span class='nv'>shape_poly</span><span class='o'>$</span><span class='nv'>x</span> <span class='o'>/</span> <span class='m'>2.5</span><span class='o'>)</span> <span class='o'>+</span> <span class='nv'>xshift</span>
  <span class='nv'>shape_poly</span><span class='o'>$</span><span class='nv'>id</span> <span class='o'>&lt;-</span> <span class='nv'>id</span>
  <span class='kr'><a href='https://rdrr.io/r/base/function.html'>return</a></span><span class='o'>(</span><span class='nv'>shape_poly</span><span class='o'>)</span>
<span class='o'>&#125;</span>

<span class='c'># specify stars </span>
<span class='nv'>sep</span> <span class='o'>&lt;-</span> <span class='m'>.75</span>
<span class='nv'>shapes</span> <span class='o'>&lt;-</span> <span class='nf'>bind_rows</span><span class='o'>(</span>
  <span class='nf'>get_shape</span><span class='o'>(</span><span class='m'>1.5</span>,<span class='nv'>sep</span>,<span class='m'>1</span><span class='o'>)</span>,
  <span class='nf'>get_shape</span><span class='o'>(</span><span class='m'>2.4</span>,<span class='nv'>sep</span>,<span class='m'>2</span><span class='o'>)</span>,
  <span class='nf'>get_shape</span><span class='o'>(</span><span class='m'>3.3</span>,<span class='nv'>sep</span>,<span class='m'>3</span><span class='o'>)</span>,
  <span class='nf'>get_shape</span><span class='o'>(</span><span class='m'>4.2</span>,<span class='nv'>sep</span>,<span class='m'>4</span><span class='o'>)</span>,
  <span class='nf'>get_shape</span><span class='o'>(</span><span class='m'>5.1</span>,<span class='nv'>sep</span>,<span class='m'>5</span><span class='o'>)</span>,
  <span class='nf'>get_shape</span><span class='o'>(</span><span class='m'>2.4</span>,<span class='o'>-</span><span class='nv'>sep</span>,<span class='m'>6</span><span class='o'>)</span>,
  <span class='nf'>get_shape</span><span class='o'>(</span><span class='m'>3.3</span>,<span class='o'>-</span><span class='nv'>sep</span>,<span class='m'>7</span><span class='o'>)</span>,
  <span class='nf'>get_shape</span><span class='o'>(</span><span class='m'>4.2</span>,<span class='o'>-</span><span class='nv'>sep</span>,<span class='m'>8</span><span class='o'>)</span>
<span class='o'>)</span>

<span class='c'># specify text</span>
<span class='nv'>msg</span> <span class='o'>&lt;-</span> <span class='nf'>bind_rows</span><span class='o'>(</span>
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"T"</span>, <span class='m'>1.2</span>, <span class='nv'>sep</span>, <span class='m'>1</span><span class='o'>)</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"h"</span>, <span class='m'>2.2</span>, <span class='nv'>sep</span>, <span class='m'>2</span><span class='o'>)</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"a"</span>, <span class='m'>3.1</span>, <span class='nv'>sep</span>, <span class='m'>3</span><span class='o'>)</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"n"</span>, <span class='m'>4.0</span>, <span class='nv'>sep</span>, <span class='m'>4</span><span class='o'>)</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"k"</span>, <span class='m'>4.8</span>, <span class='nv'>sep</span>, <span class='m'>5</span><span class='o'>)</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"Y"</span>, <span class='m'>2.2</span>, <span class='o'>-</span><span class='nv'>sep</span>, <span class='m'>6</span><span class='o'>)</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"o"</span>, <span class='m'>3.2</span>, <span class='o'>-</span><span class='nv'>sep</span>, <span class='m'>7</span><span class='o'>)</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"u"</span>, <span class='m'>3.9</span>, <span class='o'>-</span><span class='nv'>sep</span>, <span class='m'>8</span><span class='o'>)</span>  
<span class='o'>)</span>

<span class='c'># bind them</span>
<span class='nv'>msg</span><span class='o'>$</span><span class='nv'>frame</span> <span class='o'>&lt;-</span> <span class='m'>2</span>
<span class='nv'>shapes</span><span class='o'>$</span><span class='nv'>frame</span> <span class='o'>&lt;-</span> <span class='m'>1</span>
<span class='nv'>dat</span> <span class='o'>&lt;-</span> <span class='nf'>bind_rows</span><span class='o'>(</span><span class='nv'>msg</span>, <span class='nv'>shapes</span><span class='o'>)</span>

<span class='c'># use gganimate</span>
<span class='nv'>anim</span> <span class='o'>&lt;-</span> <span class='nv'>dat</span> <span class='o'>%&gt;%</span> 
  <span class='nf'>ggplot</span><span class='o'>(</span><span class='nf'>aes</span><span class='o'>(</span><span class='nv'>x</span>,<span class='nv'>y</span>,group<span class='o'>=</span><span class='nv'>id</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>+</span> 
  <span class='nf'>geom_path</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
  <span class='nf'>coord_equal</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
  <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>ylim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>2</span>, <span class='m'>3</span><span class='o'>)</span> <span class='o'>+</span> 
  <span class='nf'>theme_void</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
  <span class='nf'>theme</span><span class='o'>(</span>plot.background <span class='o'>=</span> <span class='nf'>element_rect</span><span class='o'>(</span>
    fill <span class='o'>=</span> <span class='s'>"#eeeeee"</span>, colour <span class='o'>=</span> <span class='s'>"#eeeeee"</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>+</span> 
  <span class='nf'><a href='https://gganimate.com/reference/transition_states.html'>transition_states</a></span><span class='o'>(</span><span class='nv'>frame</span><span class='o'>)</span>

<span class='c'># make it happen...</span>
<span class='nf'><a href='https://gganimate.com/reference/animate.html'>animate</a></span><span class='o'>(</span><span class='nv'>anim</span>, type <span class='o'>=</span> <span class='s'>"cairo"</span>, bg <span class='o'>=</span> <span class='s'>"#eeeeee"</span><span class='o'>)</span>
</code></pre>
<img src="figs/thankyoustars-1.gif" width="700px" style="display: block; margin: auto;" />

</div>

I am very fond of this gif, but after making it I realised there's so much I don't understand about how it works. I've had quite a lot of [experience](https://github.com/djnavarro/brownianbridge) with creating animations in R that use shadow wake to create interesting visual effects, but this was the first time I'd made one that transformed more complex objects. It wasn't clear to me how my code was ["tweening"](https://en.wikipedia.org/wiki/Inbetweening) between two rather different forms, and so -- to foreground the unsubtle metaphor in this essay -- I started exploring how such transitions are constructed.

<br>

IX. On documentation
--------------------

> Documentation is one of the most important aspects of a good package. Without it, users won't know how to use your package
>
> --Hadley Wickham, [*R Packages*](http://r-pkgs.had.co.nz/man.html)

As I write this, I am waiting for my passport to arrive. It has taken me three months of work to reach this point. Three doctors, two mental health professionals, one lawyer, and three separate governments have had to approve my gender transition, just to turn one little *M* into an *F*.

The process, so far, has unfolded like this. My therapist suggested I visit a doctor, who had to refer me to a psychiatrist; the psychiatrist had to write a letter diagnosing me with gender dysphoria; the letter went to another doctor who referred me to an endocrinologist; the endocrinologist prescribed hormones; a pathologist took blood and tested my hormone levels; the endocrinologist then wrote a letter to the government asserting I am receiving appropriate medical treatment for my gender dysphoria; I took the documents to a lawyer who checked the paperwork and certified the documents; the whole packet was sent to the South Australian state government to change my birth certificate; to obtain a passport, I filed a new set of paperwork with the Federal government; to file the paperwork I went to the post office; to pass the interview at the post office I needed a drivers licence; to get the driver's licence from the New South Wales government I had to take the birth certificate and my old licence to Road and Maritime Services; after the passport interview, the request was filed with the Passports Office; and I am now waiting to hear back from them.

As yet I have not updated my bank accounts, my medicare card, my health insurance records, the name on my lease, or my tax records. Almost every professional organisation to which I belong, most of the journals for which I have reviewed, or even just the dozens of minor accounts that we all have, they all list me as Daniel and as much as the deadnaming gets under my skin it's too much effort to try to fix them all at once.

There's a strangeness to this process though. Because getting documentation is so difficult for transgender people, transition can leave one in a strangely undocumented state for quite a time. It's very uncomfortable.

In my experience - admittedly that of the most privileged kind of trans woman, a white, middle-class one - the undocumented state of a transsexual is a curious thing. It isn't the same as that of an "undocumented worker". Unlike a person who is in a country without authorisation, my documentation *is* acceptable to the State. However, what people often do *not* accept is the link between my documents and my person. The name on my credit card, the photo on my drivers licence, the M on my passport. Each of these things are used as authentication tokens in one social context or another, and they do not match. So credentials are rarely accepted as valid without some further proof.

A few examples maybe be instructive.

-   The receptionists at a hotel who argued over whether the "Daniel" on the driver's licence is the same person as the "Danielle" for whom they have a booking, and if the man in the photo is the woman they can plainly see in front of them. While I stood there trying not to cry in shame, people staring at me.
-   When I flew through Dubai. UAE has laws against "female impersonation", I believe, and I am flagged for a "random heightened screening" (yeah, it's not random - I'm 9 from 9 now). The officer automatically genders me as a woman, takes me into the private room with a female officer. She sees the male passport and the man in the photo. There is a brief silence. My panic skyrockets. She searches my carry on baggage, smiles at me and says "thank you ma'am". I smile back, leave, and as soon as I'm out of the room I start shaking uncontrollably.
-   I lost my wallet on campus, which had all my identification in it. Luckily it had my staff card so security were able to send me an email. However I made *very* certain that my reply email to the security officer outed me as a trans woman when setting an appointment to pick it up. When I went in, she told me it was lucky I'd done so, otherwise she never would have believed the wallet was really mine.

It should go without saying that these aren't isolated incidents. Situations like these pop up over and over again. Sometimes the consequences are severe, more often they are minor. Regardless of severity, you learn to keep your guard up even in superficially innocuous situations. You start developing little habits that allow you to surreptitiously hide. Maybe you always "accidentally" cover the first name on your credit card when you go to use a "tap and pay", just to avoid being outed. Perhaps you cover the photo on your staff card when swiping in to enter a room, and so on. It's not a hard skill to learn, but after a while it starts to feel a little like identity theft. *Daniel* was a real person, and by using his bank accounts and his ID cards, *Danielle* reveals her true nature as a deceiver, an inappropriate woman stealing a man's rightful place in the world.

<br>

Two. Of letters and forms
-------------------------

If letters and documentation has played more of a role in my transition than one might intuitively think, they also occupy a curious status when constructing plots and animations. They are at once symbolic, linguistic objects -- still recognisably the same entity under quite drastic changes in font family and size -- but they must also occupy space on a plot as graphical objects themselves. Usually when drawing plots this tension isn't all that apparent. When using ggplot2, for example, the [grid](https://www.stat.auckland.ac.nz/~paul/RGraphics/chapter5.pdf) graphics model handles text as though it were any other graphical object, but at some level the system fonts have to do some of the work in translating the abstract representation into a graphical specification. This mostly works seamlessly but there are times when R doesn't handle it cleanly or in a platform-independent way, which is where packages like [showtext](https://github.com/yixuan/showtext) can come in handy, by controlling the text represention at a more primitive level.

For my purposes though, I need user-level access to this raw representation of letters so that I can use them as tweenable entities. This is where the [fontr](https://github.com/yixuan/fontr) package is handy. It's a small package that allows you to construct glyphs from font files, in one of three different forms. One thing you can do is extract a bitmap representation.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nf'><a href='https://rdrr.io/pkg/fontr/man/glyph_bitmap.html'>glyph_bitmap</a></span><span class='o'>(</span>ch<span class='o'>=</span><span class='s'>"T"</span><span class='o'>)</span> <span class='o'>%&gt;%</span> <span class='nf'><a href='https://rdrr.io/r/graphics/plot.default.html'>plot</a></span><span class='o'>(</span><span class='o'>)</span>
</code></pre>
<img src="figs/glyphbitmap-1.png" width="700px" style="display: block; margin: auto;" />

</div>

As a second possibility, the package allows you to extract the letter form in a format that mirrors how paths are specified in [SVG format](https://www.w3.org/TR/SVG/paths.html), with movement commands that specify Bézier curves and other actions.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nf'><a href='https://rdrr.io/pkg/fontr/man/glyph_outline.html'>glyph_outline</a></span><span class='o'>(</span>ch<span class='o'>=</span><span class='s'>"t"</span>, family <span class='o'>=</span> <span class='s'>"Allura"</span><span class='o'>)</span> <span class='o'>%&gt;%</span> <span class='nf'><a href='https://rdrr.io/r/utils/head.html'>head</a></span><span class='o'>(</span><span class='o'>)</span>
<span class='c'>#&gt;       x     y type</span>
<span class='c'>#&gt; 1 0.200 0.280    M</span>
<span class='c'>#&gt; 2 0.293 0.287    Q</span>
<span class='c'>#&gt; 3 0.277 0.287    B</span>
<span class='c'>#&gt; 4 0.310 0.282    Q</span>
<span class='c'>#&gt; 5 0.310 0.287    B</span>
<span class='c'>#&gt; 6 0.286 0.269    Q</span></code></pre>

</div>

For my purposes when constructing my thank you gif, the most useful fontr function was `glyph_polygon`, which extracts a representation of the letter as a set of `x` and `y` co-ordinates that specify the edges of a polygon. Using the [Allura](https://fonts.google.com/specimen/Allura) font to define the shapes, here is what it extracts

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>m_poly</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/pkg/fontr/man/glyph_polygon.html'>glyph_polygon</a></span><span class='o'>(</span>ch<span class='o'>=</span><span class='s'>"m"</span>, family <span class='o'>=</span> <span class='s'>"Allura"</span><span class='o'>)</span> 
<span class='nv'>f_poly</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/pkg/fontr/man/glyph_polygon.html'>glyph_polygon</a></span><span class='o'>(</span>ch<span class='o'>=</span><span class='s'>"f"</span>, family <span class='o'>=</span> <span class='s'>"Allura"</span><span class='o'>)</span></code></pre>

</div>

The data structure for this polygon is just a regular data frame, so it is straightforward to work with.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>m_poly</span> <span class='o'>%&gt;%</span> <span class='nf'><a href='https://rdrr.io/r/utils/head.html'>head</a></span><span class='o'>(</span><span class='o'>)</span>
<span class='c'>#&gt;         x       y</span>
<span class='c'>#&gt; 1 0.17100 0.26000</span>
<span class='c'>#&gt; 2 0.17089 0.25843</span>
<span class='c'>#&gt; 3 0.17056 0.25652</span>
<span class='c'>#&gt; 4 0.17001 0.25427</span>
<span class='c'>#&gt; 5 0.16924 0.25168</span>
<span class='c'>#&gt; 6 0.16825 0.24875</span></code></pre>

</div>

The fontr package does supply an S3 plot method, which is a nice touch because it shows you where each letter extends in the implied bounding box. Here are the shapes that it specifies for the lower case letters "m" and "f".

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>m_poly</span> <span class='o'>%&gt;%</span> <span class='nf'><a href='https://rdrr.io/r/graphics/plot.default.html'>plot</a></span><span class='o'>(</span><span class='o'>)</span>
</code></pre>
<img src="figs/glyphpolygon3-1.png" width="700px" style="display: block; margin: auto;" />
<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>f_poly</span> <span class='o'>%&gt;%</span> <span class='nf'><a href='https://rdrr.io/r/graphics/plot.default.html'>plot</a></span><span class='o'>(</span><span class='o'>)</span>
</code></pre>
<img src="figs/glyphpolygon3-2.png" width="700px" style="display: block; margin: auto;" />

</div>

And with that, the abstract representation of letters as syntactic, conceptual units has been transformed into raw graphical objects, entities that are amenable to deformation and reshaping as any other thing might be so used, in whatever fashion one might desire.

<br>

VIII. Fuck toy
--------------

An oft-noted aspect to the transition of a trans woman is the curious, almost prurient interest that others have in her body - especially if she is young and attractive. Is she going to have *the surgery* or not? Has she? Well, I'm no longer young, and I'm not the best judge of my own attractiveness, but it is nevertheless amazing to me how much interest people sometimes take in my breasts and penis, and especially in the fact that I possess both. Never in my life have other people been so intrigued by my body as they are now, and it's a little unnerving.

Until transitioning I'd never come across the term *trap*, as a term to describe a conventionally attractive transgender woman, but it seems fitting in a nasty kind of way - a trans woman is automatically considered to be deceptive if she passes (and pathetic if she does not), as though our transitions have something to do with luring men into bed. The concept of a *trap* was one I didn't know about beforehand, but all the *other* words I knew all too well, and any time I catch sight of a man surreptitiously looking at me in that particular way men do, I cannot avoid thinking them: *tranny*, *ladyboy*, *shemale*, *sissy boy*, *t-girl*, *whore*.

The last of those isn't specific to trans women of course, but it is remarkable to me how strong the association between trans women and prostitution is, both in people's minds and in the fact that so very many trans women end up in sex work. People so often presume some link between my gender and my sexual orientation, but the boring truth in my case is that I'm not a particularly sexual person and for much of my life I've viewed sexual arousal as an uncomfortable nuisance. Nevertheless, people now see me as a woman and I've had to adapt very quickly to feeling sexualised and objectified.

When I think about the manner in which my body is sexualised, I often find myself pondering the extent to which this is the same kind of objectification that cisgender women experience, versus how much is something specific to transsexual women. In my daily life, it doesn't feel any different - I get the same stares from men at construction sites and at bars, and my anxieties about the male gaze doesn't seem any different to what other women describe.

But it isn't entirely the same. In movies, the trans woman is rarely if ever "[the girl next door](https://tvtropes.org/pmwiki/pmwiki.php/Main/GirlNextDoor)" or even the poorly-written "[strong female character](https://www.themarysue.com/strong-female-characters/)". Indeed, I cannot think of a single example that I have seen -- especially among the media I consumed in my formative years -- in which a trans woman was written as anything other than a sex toy, a pathetic crossdresser, or a monster. The only role models I've had to understand my own sexuality are prostitutes and porn actresses, and if you've not seen any t-girl porn, well (through no fault of the women involved) it hasn't been the most uplifting experience I have to say.

The upshot of this - besides a constant feeling of shame - is that I find myself trapped in a strange variation of the "Madonna/Whore" dilemma that other women face. At all times I must behave like The Good Tran in public, demure and in all ways a well-behaved woman, or else my gender will be revoked. A cisgender woman who misbehaves is a bitch; a trans woman who does so is a *man*, and a perverted, disgusting one at that.

Outwardly then I must behave myself, a good, docile lady. Even so, the moment the transsexuality of my body is revealed, my good behaviour is undone. When straight men first realise I am trans, they occasionally get a particular look on their face, searching for clues that would betray my maleness. They stare intently at my face, my throat, and their eyes flick down to my breasts, lingering slightly as if we were flirting at a bar rather than in the middle of a meeting. When they don't think I am looking, I catch them staring at my crotch as if they had x-ray vision that could reveal my penis. The fact of their interest and their entitled boldness is no surprise, and perhaps it is different to how cisgender women experience things, but the *cue* that elicits this mental undressing feels particularly degrading. The fact that this appraisal is prompted specifically by the fact that my transness has been revealed (when they had been quite respectful up to this point) reminds me that I am a *thing*, and not a person.[^2]

<br>

Three. Transformation, motion and emotion
-----------------------------------------

One thing about the letter forms constructed by fontr is the fact that we can choose to render them as shapes or as paths, and there are a variety of methods for tweening from one to another. In general, animation requires making choices about *how* one should interpolate between different images, and the possibilies can vary a lot. To take as simple example, consider these two [lissajous curves](http://mathworld.wolfram.com/LissajousCurve.html). A lissajous curve is defined by two equations $$
\begin{array}{rcl}
 x(t) &=& a \sin(\omega t + \delta) \\
 y(t) &=& b \sin(t)
\end{array}
$$

To work with lissajous curves in R, I started with a simple implementation that returns a tibble containing the values of `t`, `x` and `y`.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>lissajous</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='nv'>a</span>, <span class='nv'>b</span>, <span class='nv'>w</span>, <span class='nv'>d</span>, <span class='nv'>t</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nf'>tibble</span><span class='o'>(</span>
    t <span class='o'>=</span> <span class='nv'>t</span>,
    x <span class='o'>=</span> <span class='nv'>a</span> <span class='o'>*</span> <span class='nf'><a href='https://rdrr.io/r/base/Trig.html'>sin</a></span><span class='o'>(</span><span class='nv'>w</span> <span class='o'>*</span> <span class='nv'>t</span> <span class='o'>+</span> <span class='nv'>d</span><span class='o'>)</span>,
    y <span class='o'>=</span> <span class='nv'>b</span> <span class='o'>*</span> <span class='nf'><a href='https://rdrr.io/r/base/Trig.html'>sin</a></span><span class='o'>(</span><span class='nv'>t</span><span class='o'>)</span>
  <span class='o'>)</span>
<span class='o'>&#125;</span></code></pre>

</div>

By varying the parameters fed to the function a range of different curves can be produced. Superficial differences in the inputs can lead to quite drastic forms in the output, but they are all part of a single family of entities. In this example, I produce two different curves by varying `w`.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>t</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/r/base/seq.html'>seq</a></span><span class='o'>(</span><span class='m'>0</span>, <span class='m'>30</span>, length.out <span class='o'>=</span> <span class='m'>500</span><span class='o'>)</span>
<span class='nv'>curve1</span> <span class='o'>&lt;-</span> <span class='nf'>lissajous</span><span class='o'>(</span><span class='m'>1</span>, <span class='m'>1</span>, <span class='m'>.3</span>, <span class='m'>1</span>, <span class='nv'>t</span><span class='o'>)</span>
<span class='nv'>curve2</span> <span class='o'>&lt;-</span> <span class='nf'>lissajous</span><span class='o'>(</span><span class='m'>1</span>, <span class='m'>1</span>, <span class='m'>.99</span>, <span class='m'>1</span>, <span class='nv'>t</span><span class='o'>)</span>
<span class='nf'>bind_rows</span><span class='o'>(</span>
  <span class='s'>"Curve 1"</span> <span class='o'>=</span> <span class='nv'>curve1</span>, 
  <span class='s'>"Curve 2"</span> <span class='o'>=</span> <span class='nv'>curve2</span>, 
  .id <span class='o'>=</span> <span class='s'>"id"</span>
  <span class='o'>)</span> <span class='o'>%&gt;%</span>
  <span class='nf'>ggplot</span><span class='o'>(</span><span class='nf'>aes</span><span class='o'>(</span><span class='nv'>x</span>,<span class='nv'>y</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>+</span> 
  <span class='nf'>geom_path</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
  <span class='nf'>facet_wrap</span><span class='o'>(</span><span class='o'>~</span><span class='nv'>id</span><span class='o'>)</span> <span class='o'>+</span> 
  <span class='nf'>theme_void</span><span class='o'>(</span><span class='o'>)</span>
</code></pre>
<img src="figs/lissajous2-1.png" width="700px" style="display: block; margin: auto;" />

</div>

One way to tween from one to the other is to interpolate smoothly on the parameter space of the `lissajous` function. That would produce an animation like this:

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>wvals</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/r/base/c.html'>c</a></span><span class='o'>(</span>
  <span class='nf'><a href='https://rdrr.io/r/base/seq.html'>seq</a></span><span class='o'>(</span>from <span class='o'>=</span> <span class='m'>.3</span>, to <span class='o'>=</span> <span class='m'>.99</span>, length.out<span class='o'>=</span><span class='m'>75</span><span class='o'>)</span>,
  <span class='nf'><a href='https://rdrr.io/r/base/seq.html'>seq</a></span><span class='o'>(</span>from <span class='o'>=</span> <span class='m'>.99</span>, to <span class='o'>=</span> <span class='m'>.3</span>, length.out<span class='o'>=</span><span class='m'>75</span><span class='o'>)</span>
<span class='o'>)</span>

<span class='kr'>for</span><span class='o'>(</span><span class='nv'>w</span> <span class='kr'>in</span> <span class='nv'>wvals</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nv'>pic</span> <span class='o'>&lt;-</span> <span class='nf'>lissajous</span><span class='o'>(</span><span class='m'>1</span>, <span class='m'>1</span>, <span class='nv'>w</span>, <span class='m'>1</span>, <span class='nv'>t</span><span class='o'>)</span> <span class='o'>%&gt;%</span>
    <span class='nf'>ggplot</span><span class='o'>(</span><span class='nf'>aes</span><span class='o'>(</span><span class='nv'>x</span>,<span class='nv'>y</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'>geom_path</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'>coord_equal</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>xlim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>1.5</span>,<span class='m'>1.5</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>ylim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>1.5</span>,<span class='m'>1.5</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'>theme_void</span><span class='o'>(</span><span class='o'>)</span>
  <span class='nf'><a href='https://rdrr.io/r/graphics/plot.default.html'>plot</a></span><span class='o'>(</span><span class='nv'>pic</span><span class='o'>)</span>
<span class='o'>&#125;</span>
</code></pre>
<img src="figs/lissajous3-.gif" width="700px" style="display: block; margin: auto;" />

</div>

In some cases this kind of animation is most natural, and doing this with lissajous curves highlights the manner in which the relationship between underlying parameters and the resulting curve is not always simple, much as -- to pick a completely arbitrary example -- manipulating the sex hormones that control one's endocrine system can produce non-trivial changes to a human body. But in many other cases there is *no* natural parameter space on which we can perform this interpolation, and a tweening algorithm needs to intervene more directly, manipulating the raw features of the curve or shape to produce the necessary alterations.

The [transformr](https://github.com/thomasp85/transformr) package in R, inspired by the [flubber](https://github.com/veltman/flubber) javascript library, provides a mechanism for flexibly making "best guess" tweening of shapes and curves. It makes sensible guesses as to what the most natural interpolation might look like, but then allows the user to specify an [easing function](https://easings.net/) that tells R how quickly to move along that path. In the simplest transformation one might ease linearly along the path, but by changing the easing function you can produce a variety of different effects.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>compress</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/pkg/tweenr/man/tween_state.html'>tween_state</a></span><span class='o'>(</span>
  <span class='nv'>curve1</span>, <span class='nv'>curve2</span>, 
  ease <span class='o'>=</span> <span class='s'>'linear'</span>, 
  nframes <span class='o'>=</span> <span class='m'>100</span>, 
  id <span class='o'>=</span> <span class='nv'>t</span>
<span class='o'>)</span> 

<span class='nv'>snap_back</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/pkg/tweenr/man/tween_state.html'>tween_state</a></span><span class='o'>(</span>
  <span class='nv'>curve2</span>, <span class='nv'>curve1</span>, 
  ease <span class='o'>=</span> <span class='s'>'elastic-out'</span>, 
  nframes <span class='o'>=</span> <span class='m'>30</span>, 
  id <span class='o'>=</span> <span class='nv'>t</span><span class='o'>)</span> 

<span class='nv'>bind_tweens</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='nv'>forward</span>, <span class='nv'>backward</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nv'>nframes</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/r/base/Extremes.html'>max</a></span><span class='o'>(</span><span class='nv'>forward</span><span class='o'>$</span><span class='nv'>.frame</span><span class='o'>)</span>
  <span class='nv'>backward</span> <span class='o'>&lt;-</span> <span class='nv'>backward</span> <span class='o'>%&gt;%</span> <span class='nf'>mutate</span><span class='o'>(</span>.frame <span class='o'>=</span> <span class='nv'>.frame</span> <span class='o'>+</span> <span class='nv'>nframes</span><span class='o'>)</span>
  <span class='nv'>anim</span> <span class='o'>&lt;-</span> <span class='nf'>bind_rows</span><span class='o'>(</span><span class='nv'>forward</span>, <span class='nv'>backward</span><span class='o'>)</span>
  <span class='kr'><a href='https://rdrr.io/r/base/function.html'>return</a></span><span class='o'>(</span><span class='nv'>anim</span><span class='o'>)</span>
<span class='o'>&#125;</span>

<span class='nv'>drawframe</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='nv'>data</span>, <span class='nv'>f</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nv'>pic</span> <span class='o'>&lt;-</span> <span class='nv'>data</span> <span class='o'>%&gt;%</span> 
    <span class='nf'><a href='https://rdrr.io/r/stats/filter.html'>filter</a></span><span class='o'>(</span><span class='nv'>.frame</span> <span class='o'>==</span> <span class='nv'>f</span><span class='o'>)</span> <span class='o'>%&gt;%</span>
    <span class='nf'>ggplot</span><span class='o'>(</span><span class='nf'>aes</span><span class='o'>(</span><span class='nv'>x</span>, <span class='nv'>y</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>+</span>  
    <span class='nf'>geom_path</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'>coord_equal</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>xlim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>1.5</span>,<span class='m'>1.5</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>ylim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>1.5</span>,<span class='m'>1.5</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'>theme_void</span><span class='o'>(</span><span class='o'>)</span>
  <span class='nf'><a href='https://rdrr.io/r/graphics/plot.default.html'>plot</a></span><span class='o'>(</span><span class='nv'>pic</span><span class='o'>)</span>
<span class='o'>&#125;</span>

<span class='nv'>anim</span> <span class='o'>&lt;-</span> <span class='nf'>bind_tweens</span><span class='o'>(</span><span class='nv'>compress</span>, <span class='nv'>snap_back</span><span class='o'>)</span>
<span class='kr'>for</span><span class='o'>(</span><span class='nv'>f</span> <span class='kr'>in</span> <span class='m'>1</span><span class='o'>:</span><span class='m'>130</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>anim</span>, <span class='nv'>f</span><span class='o'>)</span> 
</code></pre>
<img src="figs/lissajous-.gif" width="700px" style="display: block; margin: auto;" />

</div>

In this example, the first 100 frames of the animation slowly, linearly interpolate from the first to the second curve, giving the impression of a continuous process of coiling or perhaps compression. In the second stage, an elastic easing unfolds over a mere 30 frames, giving the impression of a more violent unwinding in which the curve snaps back to a natural, preferred state.

<br>

VII. Talking with men
---------------------

> Yes, people of both genders pop up at events to hold forth on irrelevant things and conspiracy theories, but the out-and-out confrontational confidence of the totally ignorant is, in my experience, gendered. Men explain things to me, and other women, whether or not they know what they're talking about.
>
> --Rebecca Solnit, [*Men Explain Things To Me*](https://www.amazon.com.au/Men-Explain-Things-Rebecca-Solnit/dp/1608464660)

Gender transition makes the misogynistic nature of our society painfully visible. People automatically gender others - we can hardly prevent ourselves. Much like Julia Serano (2007) describes in her book *Whipping Girl*, I thought there would be a period in which I would be ambiguous and people would act uncertainly around me. That hasn't happened. Instead, almost overnight it would seem, strangers default behaviour towards me just *flipped*. One day I was a man; the next I was a woman. And oh my, the difference in behaviour. People stand closer, they touch me, they smile at me, men flirt with me, hold doors open for me, expect me to enter the elevator before them. All of a sudden I am a "darling", a "honey" and oh how very "beautiful" I am now. There is a new language to describe me, and only some of it is innocuous.[^3]

Most of the changes have come as little surprise. What *has* come as a shock, though, is how quickly my professional credibility has evaporated among (surprisingly many) people who did not know me pre-transition. For instance, the one form of male privilege that I have unambiguously held from the beginning was the presumption that I am logical, mathematical, analytical in my thinking. If you look at my publication record, it's pretty obvious that this is indeed how I work - as a man I was even awarded the William K. Estes New Investigator Award by the Society for Mathematical Psychology many years ago, so I can't possibly be entirely incompetent. Nevertheless, if I am to judge by the behaviour of a great many of my male colleages these intellectual qualities appear to have been tied to my testosterone level or something. *Daniel* was obviously a skilled statistical thinker, *Danielle* is constantly subjected to sharply aggressive questioning. She is naive, emotional, flighty, and easily dismissed by Important Men with Big Ideas.[^4]

The effect size on this change is *remarkable*, and the benefit of "having lived both sides" is being able to see how quickly men's behaviour towards me has shifted. I've had men with a tenth of my statistical training tell me I don't understand how to compute Bayes rule (I'm not kidding), very junior male colleagues tell me they're being "firm" with me, I've had men explain at great length how Bayes factors work (often incorrectly I might add), and I've been lectured condescendingly about how to run a simple cross-validation. I've had men dispute my standing to comment on gender transition, or just plain *ignore* me when I speak about this. I've had ...

... actually, you know what? I'm going to stop listing examples. Because here's the thing - at this point you already believe me, or you never will. Evidence doesn't seem to matter much in this conversation. Men always seem to have excuses for why *their* behaviour is different. *Other* men mansplain; I'm just trying to help. *Other* men harass; I'm just being critical. *Other* men sealion; I'm just asking questions. There's always another excuse, always another rationalisation for bad behaviour, and I've stopped taking these explanations seriously.

Rather like my esteemed cisgender counterparts who were a little faster on the uptake than I have been, [I have run out of fucks to give](https://www.mcsweeneys.net/articles/faq-the-status-of-the-shits-women-have-left-to-give).

<br>

Four. Detaching the tween from the geom
---------------------------------------

When tweening the lissajous curves, or indeed the letters and stars in the original thank you gif, the graphical objects were represented as open paths rather than closed polygons. When using *gganimate* in the original gif, the choice of tweening method was selected automatically (`tween_state` in this case), whereas in the lissajous curve example I specified the use of `tween_state` directly. However, there is nothing stopping us from making different choices. For example, in the animation below the tweening function is `tween_polygon` from the *transformr* package, which respects the fact that the objects are closed contours, but I have used `geom_path` to render only the outlines of the objects in each frame.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>loop</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='nv'>from</span>, <span class='nv'>to</span>, <span class='nv'>by</span>, <span class='nv'>...</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nv'>forward</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/r/base/by.html'>by</a></span><span class='o'>(</span><span class='nv'>from</span>, <span class='nv'>to</span>, <span class='nv'>...</span><span class='o'>)</span>
  <span class='nv'>backward</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/r/base/by.html'>by</a></span><span class='o'>(</span><span class='nv'>to</span>, <span class='nv'>from</span>, <span class='nv'>...</span><span class='o'>)</span>
  <span class='kr'><a href='https://rdrr.io/r/base/function.html'>return</a></span><span class='o'>(</span><span class='nf'>bind_tweens</span><span class='o'>(</span><span class='nv'>forward</span>, <span class='nv'>backward</span><span class='o'>)</span><span class='o'>)</span>
<span class='o'>&#125;</span>

<span class='nv'>drawframe</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='nv'>data</span>, <span class='nv'>f</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nv'>pic</span> <span class='o'>&lt;-</span> <span class='nv'>data</span> <span class='o'>%&gt;%</span> 
    <span class='nf'><a href='https://rdrr.io/r/stats/filter.html'>filter</a></span><span class='o'>(</span><span class='nv'>.frame</span> <span class='o'>==</span> <span class='nv'>f</span><span class='o'>)</span> <span class='o'>%&gt;%</span>
    <span class='nf'>ggplot</span><span class='o'>(</span><span class='nf'>aes</span><span class='o'>(</span>x<span class='o'>=</span><span class='nv'>x</span>, y<span class='o'>=</span><span class='nv'>y</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>+</span>  
    <span class='nf'>geom_path</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>xlim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>.5</span>,<span class='m'>1</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>ylim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>.5</span>,<span class='m'>1</span><span class='o'>)</span> <span class='o'>+</span>     
    <span class='nf'>coord_equal</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'>theme_void</span><span class='o'>(</span><span class='o'>)</span>
  <span class='nf'><a href='https://rdrr.io/r/graphics/plot.default.html'>plot</a></span><span class='o'>(</span><span class='nv'>pic</span><span class='o'>)</span>
<span class='o'>&#125;</span>

<span class='nv'>anim</span> <span class='o'>&lt;-</span> <span class='nf'>loop</span><span class='o'>(</span><span class='nv'>m_poly</span>, <span class='nv'>f_poly</span>, <span class='nv'>tween_polygon</span>,
             ease <span class='o'>=</span> <span class='s'>"cubic-in-out"</span>, nframes <span class='o'>=</span> <span class='m'>50</span><span class='o'>)</span>
<span class='kr'>for</span><span class='o'>(</span><span class='nv'>f</span> <span class='kr'>in</span> <span class='m'>1</span><span class='o'>:</span><span class='m'>100</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>anim</span>, <span class='nv'>f</span><span class='o'>)</span>
</code></pre>
<img src="figs/lettertween-.gif" width="700px" style="display: block; margin: auto;" />

</div>

Notice that the tweening algorithm will create and delete objects as necessary to make the transition work.

<br>

VI. The kindness of R-Ladies
----------------------------

In the very early stages of transition, one of my friends - a much younger woman who had transitioned a few years before me - explained the concept of the *sisterhood* to me, as this abstract knowledge that other women will always be there for you. The idea that there is this invisible, soft network of shared experiences that [you can call on](https://doi.org/10.1073/pnas.1721438116), that you can contribute to, and that women often rely upon as a survival tool sounded utterly incredible, and alien, to me. I've been on my own for 40 years. Men were no use to me whatsoever, but I was certainly not a part of a woman's world, and not part of the sisterhood.[^5]

In retrospect, I realise how many mistakes I have made that could have been avoided if I'd been able to ask advice *as* a woman. How many physically dangerous situations I ended up in because I'd not been taught to listen to my own Fear properly. How many times the whisper net could have kept me safe but instead I took a beating.

As I grew older, I started understanding - at least in the abstract - how women got by in abusive situations by calling on this network, but I never imagined I'd be eligible to be a part of it. I might call myself a woman, I might live as one, but I would always be suspect because of my past or my penis. I'd not have held grudges against any woman being suspicious, to be honest, and at a gut level I sort of get where trans-exclusionary feminists are coming from because I don't fucking trust men either and if someone wanted to ascribe original sin to me I guess I'd live with that.[^6]

It was my own students - especially the women - who gave me the first hints that it wasn't going to be like that. Most younger folks didn't grow up in the intensely transphobic world I did, and it's not as big a deal to them. When it became clear that what I was doing was in fact gender transition, they just *asked* what pronoun I wanted them to use or what name I wanted, as if it were no big deal. I guess that in their world it really isn't a big deal, but it had a big effect. One student referred to me as *she* in a thesis, and another woman -- the wonderful Jen Richmond -- noticed and she smoothly adopted it without my ever saying a word. I'd never have been able to ask.

Kindness propagates in a delightful way, and when Jen floated the idea of starting a [Sydney R-Ladies chapter](https://rladiessydney.org/) I couldn't have been happier to take part. I'd wanted initially to keep a low profile, maybe just maintain the website while all the "real" women took the more visible roles, but the other organisers seemed impervious to my internalised transphobia and gave me a lot more credit than frankly I felt I deserved.

[R-Ladies](https://rladies.org/) has been an amazing thing, and my first real experience of what women mean when they talk about sisterhood. Without question I was added to the R-Ladies slack, and even though I tried *really* hard to keep a low profile (because hey, I'm not a real woman right?) it was pretty clear I was welcome there. For so long though I was scared, in the early days. Maybe it's a "don't ask don't tell" thing. Maybe there are hidden transphobes on the group. Maybe I'm not even a real trans woman anyway. I did what I always do by default - kept my head down and my mouth shut.

Then one day a Bad Thing happened on the internet.

A thing I love about the R-Ladies culture, and a lot of the culture around R on twitter, is that it really is a kind, welcoming and inclusive space built around rigorous quantitative methods. The same cannot be said for psychology's "open science" community. I bear a great deal of love for open science, but the online culture around it? Not so much. Somehow, I had managed to survive as a trans woman on the internet without being subject to transphobic harassment just fine until I started participating in the self-styled "open science" discussion in psychology and ever since then it's been largely non-stop. There have been two big incidents, one involving a Certain Science Journalist[^7] and the realisation that -- despite being a quantitative social scientist *and* a trans woman -- my opinion on the quality (or lack thereof) of much of science journalism surrounding transgender issues means nothing because some cisgender man on the internet actually met the journalist one time and thought him a nice enough chap. Sigh.

The other one ... well, look, the last time you expressed disappointment with some of your scientific colleagues, how did it end? I'm guessing it didn't end with someone taking your email address and signing you up to a "dating" site that looks suspiciously similar to a mail order bride service, right?

Well, that *is* what happened to me, and despite the fact that it was their pretty terrible rhetoric that had attracted the transphobic trolls onto my feed in the first place, very few of my psychology colleagues were the tiniest bit of help. At best they expressed regret -- after the fact, of course -- that it happened.

The R-Ladies were amazing though. I copy and pasted some of the tweets I was getting onto the slack, and explained how scared I felt. When I posted, I had no idea whether I was really going to get support or whether I was about to unearth another vein of hidden transphobia. The response could not have been more beautiful. Everyone, all these wonderful women who I had admired from afar for so long, all popped up in the slack channel not just sympathetic, but *angry* on my behalf. Ever since then, I have known, at a gut level, that I am safe with R-Ladies. I've never felt safe before.

It's rather nice.

<br>

Five. Comparing paths with polygons
-----------------------------------

In the original thank you gif, I chose to represent the letters and stars as paths so when tweening between them the `tween_path` function broke the shapes into curves and interpolated between them. When this method is applied to the "m to f" transformation, the result looks like this,

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>anim</span> <span class='o'>&lt;-</span> <span class='nf'>loop</span><span class='o'>(</span><span class='nv'>m_poly</span>, <span class='nv'>f_poly</span>, <span class='nv'>tween_path</span>,
             ease <span class='o'>=</span> <span class='s'>"cubic-in-out"</span>, nframes <span class='o'>=</span> <span class='m'>50</span><span class='o'>)</span>
<span class='kr'>for</span><span class='o'>(</span><span class='nv'>f</span> <span class='kr'>in</span> <span class='m'>1</span><span class='o'>:</span><span class='m'>100</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>anim</span>, <span class='nv'>f</span><span class='o'>)</span>
</code></pre>
<img src="figs/pathtween-.gif" width="700px" style="display: block; margin: auto;" />

</div>

In contrast, tweening between the letters as polygons gives a rather different transition between states

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>anim</span> <span class='o'>&lt;-</span> <span class='nf'>loop</span><span class='o'>(</span><span class='nv'>m_poly</span>, <span class='nv'>f_poly</span>, <span class='nv'>tween_polygon</span>,
             ease <span class='o'>=</span> <span class='s'>"cubic-in-out"</span>, nframes <span class='o'>=</span> <span class='m'>50</span><span class='o'>)</span>
<span class='kr'>for</span><span class='o'>(</span><span class='nv'>f</span> <span class='kr'>in</span> <span class='m'>1</span><span class='o'>:</span><span class='m'>100</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>anim</span>, <span class='nv'>f</span><span class='o'>)</span>
</code></pre>
<img src="figs/polygontween-.gif" width="700px" style="display: block; margin: auto;" />

</div>

Neither version seems inherently more aesthetically pleasing to me. The choice for which one to use would seem to depend on whether you want to achieve with your tweening. However, there are some trickier issues that pop up when you adopt the polygon based approach, due to the fact that letters are complicated shapes that can contain holes.

<br>

V. Dehimanisation
-----------------

There's a lot written about the complicated relationships between transgender lives and traditional notions of sexism, misogyny, and in particular the concept of *male privilege*. Do trans women benefit from it? Do trans men acquire it? What implications should an analysis of male privilege have for the transgender rights movement?[^8]

As much as I am a firm believer that male privilege exists in our society, I think it's an abstraction that comprises many, many advantages -- both large and small -- that men are given over women, and when it comes to transgender lives the abstractions start to break down. If you read what trans women have to say about their own experiences with "male privilege" you find that it varies a lot. Some women talk about having experience male privileges that evaporated after transition, others tell a story of never really receiving male privilege at all, while still others -- myself include -- give an answer that boils down to "it's complicated".

In one of my wittier moments I referred to the process of gender transition as *dehimanisation*, stealing unashamedly from Kate Manne's concept of ["himpathy"](https://www.nytimes.com/2018/09/26/opinion/brett-kavanaugh-hearing-himpathy.html). As I have transitioned, I lost my status as a "default" human (a man) and became a member of a marked category (women). More than that though, I joined a special subclass of woman (trans women) against whom it is surprisingly acceptable to openly discriminate. That's not to say that there isn't a staggering amount of discrimination against cisgender women. On the contrary, it is depressingly common. Rather, what I mean to say here is that most of the time people are aware that sexism is wrong and so they are expected to pretend they don't discriminate against cis women. With trans women, there's no pretense whatsoever. We're just *things*.[^9]

Once stripped of my status as *him*, the dehumanisation could begin. The loss of male privilege that trans women experience upon transition is pretty well documented, and I won't rehash it here (but hey, [here's a random example](https://twitter.com/delaneykingrox/status/1090402436995473408) from a couple of days ago). The trickier question to answer is whether we ever had it to begin with, and here it seems that the experiences of trans women vary quite substantially. As such I can't comment about the general case; all I can do is say something about my own life.

My experience has been one of *privilege trading*. By virtue of having been born male I was accorded certain privileges. One that I've mentioned a few times is the fact that I was considered an appropriate person to study mathematics or science. Unlike some of the other male privileges that one I managed to get a lot of mileage out of, and even after transition I've had *some* success in preserving it, though as illustrated above even that one is dissolving a little.

Other forms of male privilege were always a little more contingent or fragile. For instance, men typically don't fear being raped, and like most men I didn't fear it.[^10] Until it happened to me, that is. Many, many years later I *still* struggle to find the words.[^11] I physically cannot seem to speak her name. I nearly vomit when I smell a similar perfume. I have a visceral *disgust* for anyone who speaks with her accent. Even women who look a bit like her irrationally annoy me. The trauma response is pretty severe, yet remarkably (to me at least) it took years before I even understood the pattern. In any case, once you've actually *been* raped, any feelings of safety that you might have had are all pretty much lost.

These two examples I think highlight the contrast I've experienced. There are some kinds of male privilege that were just "there" from the beginning, largely inalienable until I transitioned. Others were things I could have had, but my experiences led to me losing them or not getting the advantages I might have had.

The big complication was that while I was certainly eligible for male privilege, the appalling state of my mental health rendered a lot of it unusable. Ever since my early teens I have struggled with severe depression and anxiety. I went through a phase of severe self harm, and I came pretty close to a suicide attempt in college. That didn't do my undergraduate education a lot of help. Underpinning the whole thing was an unexamined sense of disgust and self-loathing, a deep belief in my fundamental unworthiness as a person.

Looking back, my unwillingness to face up to how I felt about gender looks a lot like a trade-off: purchasing a form of male privilege in exchange for my mental health. As I got older and transgender identities started to become less stigmatised, it became easier to be honest about how I felt. From my personal point of view, it's been a good trade. Male privilege is no good to you if you kill yourself out of shame and disgust. I do wish the world would treat women with more respect, and I tire of the endless misogyny, but there's no way I'd go back. Quite literally, it would drive me crazy.

<br>

Six. Holes
----------

Cutting holes in a shape produces an awkward problem for the typical use case. The gganimate package relies on transformr to compute the tween, and the `tween_polygon` function is smart enough that it can detect objects with holes. In the representation that fontr produces, the hole is produced by including a row of `NA` values. To see this, here is how it is represented for the letter f:

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>f_poly</span><span class='o'>[</span><span class='m'>341</span><span class='o'>:</span><span class='m'>350</span>,<span class='o'>]</span>
<span class='c'>#&gt;            x        y</span>
<span class='c'>#&gt; 341 -0.00440 -0.32080</span>
<span class='c'>#&gt; 342 -0.00480 -0.32160</span>
<span class='c'>#&gt; 343 -0.00520 -0.32240</span>
<span class='c'>#&gt; 344 -0.00560 -0.32320</span>
<span class='c'>#&gt; 345 -0.00600 -0.32400</span>
<span class='c'>#&gt; 346 -0.00600 -0.32400</span>
<span class='c'>#&gt; 347       NA       NA</span>
<span class='c'>#&gt; 348  0.43500  0.48200</span>
<span class='c'>#&gt; 349  0.43823  0.48777</span>
<span class='c'>#&gt; 350  0.44112  0.49348</span></code></pre>

</div>

However, while `tween_polygon` is flexible enough to represent this the way we'd like it to be represented, the `geom_polygon` function in ggplot2 is not. This has been [noted before](https://rstudio-pubs-static.s3.amazonaws.com/58401_1e87f6fe73e14bafbe1f3ce3df85c99e.html). To see this, let's modify the `drawframe` function so that it calls `geom_polygon` instead of `geom_path` and -- just so that we can see what is happening -- we'll render the polygons as partially transparent objects (`alpha = .5`).

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>drawframe</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='nv'>data</span>, <span class='nv'>f</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nv'>pic</span> <span class='o'>&lt;-</span> <span class='nv'>data</span> <span class='o'>%&gt;%</span> 
    <span class='nf'><a href='https://rdrr.io/r/stats/filter.html'>filter</a></span><span class='o'>(</span><span class='nv'>.frame</span> <span class='o'>==</span> <span class='nv'>f</span><span class='o'>)</span> <span class='o'>%&gt;%</span>
    <span class='nf'>ggplot</span><span class='o'>(</span><span class='nf'>aes</span><span class='o'>(</span>x<span class='o'>=</span><span class='nv'>x</span>, y<span class='o'>=</span><span class='nv'>y</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>+</span>  
    <span class='nf'>geom_polygon</span><span class='o'>(</span>alpha<span class='o'>=</span><span class='m'>.5</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>xlim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>.5</span>,<span class='m'>1</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>ylim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>.5</span>,<span class='m'>1</span><span class='o'>)</span> <span class='o'>+</span>     
    <span class='nf'>coord_equal</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'>theme_void</span><span class='o'>(</span><span class='o'>)</span>
  <span class='nf'><a href='https://rdrr.io/r/graphics/plot.default.html'>plot</a></span><span class='o'>(</span><span class='nv'>pic</span><span class='o'>)</span>
<span class='o'>&#125;</span>
<span class='nv'>anim</span> <span class='o'>&lt;-</span> <span class='nf'>loop</span><span class='o'>(</span><span class='nv'>m_poly</span>, <span class='nv'>f_poly</span>, <span class='nv'>tween_polygon</span>,
             ease <span class='o'>=</span> <span class='s'>"cubic-in-out"</span>, nframes <span class='o'>=</span> <span class='m'>50</span><span class='o'>)</span>
<span class='kr'>for</span><span class='o'>(</span><span class='nv'>f</span> <span class='kr'>in</span> <span class='m'>1</span><span class='o'>:</span><span class='m'>100</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>anim</span>, <span class='nv'>f</span><span class='o'>)</span>
</code></pre>
<img src="figs/polygontween2-.gif" width="700px" style="display: block; margin: auto;" />

</div>

There are indeed two polygons here, the outer one and the inner one, but instead of rendering it as a *single* shape with a hole in it, `geom_polygon` has drawn two filled shapes, one over the top of the other. The only reason you can see the inner shape at all is due to the partial transparency. Fortunately, this is a problem that isn't too difficult to solve with the assistance of the [ggpolypath](https://github.com/mdsumner/ggpolypath) package. In the code below I have modified the `drawframe` function to call the `geom_polypath` function in place of the `geom_polygon` function, and it works rather nicely...

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>drawframe</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='nv'>data</span>, <span class='nv'>f</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nv'>df</span> <span class='o'>&lt;-</span> <span class='nv'>data</span> <span class='o'>%&gt;%</span> 
    <span class='nf'><a href='https://rdrr.io/r/stats/filter.html'>filter</a></span><span class='o'>(</span><span class='nv'>.frame</span> <span class='o'>==</span> <span class='nv'>f</span><span class='o'>)</span>
  <span class='nv'>df</span><span class='o'>$</span><span class='nv'>branch</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/r/base/NA.html'>is.na</a></span><span class='o'>(</span><span class='nv'>df</span><span class='o'>$</span><span class='nv'>x</span><span class='o'>)</span>
  <span class='nv'>df</span><span class='o'>$</span><span class='nv'>branch</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/r/base/cumsum.html'>cumsum</a></span><span class='o'>(</span><span class='nv'>df</span><span class='o'>$</span><span class='nv'>branch</span><span class='o'>)</span> <span class='o'>+</span> <span class='m'>1</span>
  <span class='nv'>pic</span> <span class='o'>&lt;-</span> <span class='nv'>df</span> <span class='o'>%&gt;%</span>
    <span class='nf'><a href='https://rdrr.io/r/stats/filter.html'>filter</a></span><span class='o'>(</span><span class='o'>!</span><span class='nf'><a href='https://rdrr.io/r/base/NA.html'>is.na</a></span><span class='o'>(</span><span class='nv'>x</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>%&gt;%</span>
    <span class='nf'>ggplot</span><span class='o'>(</span><span class='nf'>aes</span><span class='o'>(</span>x<span class='o'>=</span><span class='nv'>x</span>, y<span class='o'>=</span><span class='nv'>y</span>, group<span class='o'>=</span><span class='nv'>branch</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>+</span>  
    <span class='nf'><a href='https://rdrr.io/pkg/ggpolypath/man/geom_polypath.html'>geom_polypath</a></span><span class='o'>(</span>show.legend <span class='o'>=</span> <span class='kc'>FALSE</span>, 
                  fill<span class='o'>=</span><span class='s'>"black"</span>, alpha <span class='o'>=</span> <span class='m'>.5</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>xlim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>.5</span>,<span class='m'>1</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>ylim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>.5</span>,<span class='m'>1</span><span class='o'>)</span> <span class='o'>+</span>     
    <span class='nf'>coord_equal</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'>theme_void</span><span class='o'>(</span><span class='o'>)</span>
  <span class='nf'><a href='https://rdrr.io/r/graphics/plot.default.html'>plot</a></span><span class='o'>(</span><span class='nv'>pic</span><span class='o'>)</span>
<span class='o'>&#125;</span>
<span class='kr'>for</span><span class='o'>(</span><span class='nv'>f</span> <span class='kr'>in</span> <span class='m'>1</span><span class='o'>:</span><span class='m'>100</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>anim</span>, <span class='nv'>f</span><span class='o'>)</span>
</code></pre>
<img src="figs/polygontween3-.gif" width="700px" style="display: block; margin: auto;" />

</div>

...or at least it did in 2019. Something changed in the packages in the interim and I'm too tired to figure it out right now.

<br>

IV. Mister Hurricane
--------------------

> Pain is an essential part of the grooming process, and that is not accidental. Plucking the eyebrows, shaving under the arms, wearing a girdle, learning to walk in high-heeled shoes, having one's nose fixed, straightening or curling one's hair ---these things hurt. The pain, of course, teaches an important lesson: no price is too great, no process too repulsive, no operation too painful for the woman who would be beautiful.
>
> -- Andrea Dworkin, [*Woman Hating*](https://www.feministes-radicales.org/wp-content/uploads/2010/11/Andrea-DWORKIN-Woman-Hating-A-Radical-Look-at-Sexuality-1974.pdf)

On occasions I wonder how many hours, days, weeks of my life I have spent having medical lasers play across almost every part of my body, how many times I have bitten my lip suppressing the urge to scream as the pain sears across my skin. How many pills have I taken? How many mornings spent with the vile aftertaste of a spironolactone tablet lingering in my mouth, and how many more times will I do that?

Besides the pain, there's a slightly degrading feel to the whole process. Playing out the role of the Good Tran, being properly feminine for the psychiatrist to get the letter. Showing my breasts to the doctor and feeling exposed in a way I wouldn't have before. Pulling down my skirt to have a block of crystalline estrogen implanted in my buttocks. Explaining awkwardly to the TSA lady that the millimeter wave scanner is detecting an "anomaly in the groin region" because that's where my penis is.

Despite the great many indignities, I don't feel at all inclined to stop, and one might ask why. I certainly don't enjoy any of those things, but the truth of the matter is that they're better than any of the alternatives.

> Can you imagine livin' one more day <br> With a beast right up in your face <br> Can see me dyin' in this house, in any house <br> For a man in vain <br> Blinded by the Hurricane <br>
>
> --Beast, [*Mr. Hurricane*](https://www.youtube.com/watch?v=7nol7e9HJXg)

When I started taking hormones my sex drive went dead for a long time, and honestly I was grateful for that. It took a long time to be able to say this out loud but for most of my life erections have felt gross and orgasms were a complete waste of time and a *deep* disappointment to me. Sex itself can be enjoyable, of course, but sexual arousal -- and the irritating frequency with which it would happen -- always seemed like one of life's annoyances. Having that abruptly vanish was a huge relief.

It's an interesting thing to have it start to return. As my body has started to reshape itself, other things have followed with it. I have breasts but the sexual response to having my breasts touched is mirrored in my penis. I'm... struggling to work out how to accommodate the seeming contradiction here, and as I haven't yet been able to find any good primers on ladyboy puberty,[^12] I'm kind of making it up as I go along. It's weird, but I'll confess it actually does feel more natural to me than my sexual response ever used to. Go figure.

Testosterone... no, I don't miss it. I'd get angry when I didn't want to, and my the tears wouldn't come when I felt like they should. It felt like... well, per the quotes above and below... a hurricane. I'm might be emotional now, but I was *angry* then. I didn't want to be angry -- anger makes me uncomfortable, even my own, and I shied away from any expression of that anger -- but it was the only thing I could feel. I worked for years to try to separate depression and anxiety from anger, to understand why anger was so central to what I was. Some part of that was social conditioning, no doubt, but honestly? When I consider how rapidly and how completely the hormones have changed me, I'm a little doubtful that social conditioning and placebo effects are the whole story. But of course, I might be wrong.

Most importantly though, the thing that has changed is my external appearance. The hormones and laser treatment together, combined with my having learned the very basics of how to present myself as a woman, means that when I see myself in the mirror the face I see is that of a woman. I can't *not* see her as a woman. Even if I try to see Daniel in the mirror, he is gone. The only person I can see is Danielle.[^13]

No price is too great, no medication to repulsive, no laser too painful for the woman who would see *herself* in the mirror.

> So I stay a while <br> Knife in my side <br> While I slowly died <br> Defeat from the inside <br> Now I scream 'til the end of the day <br> Never again, Mr. Hurricane <br> <br> -- Beast, *Mr Hurricane*

<br>

Seven. Bookend states
---------------------

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nf'>font_add_google</span><span class='o'>(</span><span class='s'>"Allura"</span><span class='o'>)</span>
<span class='nv'>na_row</span> <span class='o'>&lt;-</span> <span class='nf'>tibble</span><span class='o'>(</span>x <span class='o'>=</span> <span class='kc'>NA</span>, y <span class='o'>=</span> <span class='kc'>NA</span>, id <span class='o'>=</span> <span class='kc'>NA</span><span class='o'>)</span>

<span class='nv'>male</span> <span class='o'>&lt;-</span> <span class='nf'>bind_rows</span><span class='o'>(</span>
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"M"</span>, <span class='m'>2</span>, <span class='m'>0</span>, <span class='m'>1</span><span class='o'>)</span>, <span class='nv'>na_row</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"a"</span>, <span class='m'>4.15</span>, <span class='m'>0</span>, <span class='m'>2</span><span class='o'>)</span>, <span class='nv'>na_row</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"l"</span>, <span class='m'>5.05</span>, <span class='m'>0</span>, <span class='m'>3</span><span class='o'>)</span>, <span class='nv'>na_row</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"e"</span>, <span class='m'>5.55</span>, <span class='m'>0</span>, <span class='m'>4</span><span class='o'>)</span>, <span class='nv'>na_row</span>
<span class='o'>)</span>

<span class='nv'>female</span> <span class='o'>&lt;-</span> <span class='nf'>bind_rows</span><span class='o'>(</span>
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"F"</span>, <span class='m'>1</span>, <span class='m'>0</span>, <span class='m'>1</span><span class='o'>)</span>, <span class='nv'>na_row</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"e"</span>, <span class='m'>1.8</span>, <span class='m'>0</span>, <span class='m'>2</span><span class='o'>)</span>, <span class='nv'>na_row</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"m"</span>, <span class='m'>2.5</span>, <span class='m'>0</span>, <span class='m'>3</span><span class='o'>)</span>, <span class='nv'>na_row</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"a"</span>, <span class='m'>3.7</span>, <span class='m'>0</span>, <span class='m'>4</span><span class='o'>)</span>, <span class='nv'>na_row</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"l"</span>, <span class='m'>4.6</span>, <span class='m'>0</span>, <span class='m'>5</span><span class='o'>)</span>, <span class='nv'>na_row</span>,
  <span class='nf'>get_letter</span><span class='o'>(</span><span class='s'>"e"</span>, <span class='m'>5.1</span>, <span class='m'>0</span>, <span class='m'>6</span><span class='o'>)</span>, <span class='nv'>na_row</span>
<span class='o'>)</span>

<span class='nv'>drawframe</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='nv'>data</span>, <span class='nv'>f</span>, <span class='nv'>alpha</span> <span class='o'>=</span> <span class='m'>.5</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='nv'>df</span> <span class='o'>&lt;-</span> <span class='nv'>data</span> <span class='o'>%&gt;%</span> 
    <span class='nf'><a href='https://rdrr.io/r/stats/filter.html'>filter</a></span><span class='o'>(</span><span class='nv'>.frame</span> <span class='o'>==</span> <span class='nv'>f</span><span class='o'>)</span>
  <span class='nv'>df</span><span class='o'>$</span><span class='nv'>branch</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/r/base/NA.html'>is.na</a></span><span class='o'>(</span><span class='nv'>df</span><span class='o'>$</span><span class='nv'>x</span><span class='o'>)</span>
  <span class='nv'>df</span><span class='o'>$</span><span class='nv'>branch</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/r/base/cumsum.html'>cumsum</a></span><span class='o'>(</span><span class='nv'>df</span><span class='o'>$</span><span class='nv'>branch</span><span class='o'>)</span> <span class='o'>+</span> <span class='m'>1</span>
  <span class='nv'>pic</span> <span class='o'>&lt;-</span> <span class='nv'>df</span> <span class='o'>%&gt;%</span>
    <span class='nf'><a href='https://rdrr.io/r/stats/filter.html'>filter</a></span><span class='o'>(</span><span class='o'>!</span><span class='nf'><a href='https://rdrr.io/r/base/NA.html'>is.na</a></span><span class='o'>(</span><span class='nv'>x</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>%&gt;%</span>
    <span class='nf'>ggplot</span><span class='o'>(</span><span class='nf'>aes</span><span class='o'>(</span><span class='nv'>x</span>, <span class='nv'>y</span>, group<span class='o'>=</span><span class='nv'>branch</span><span class='o'>)</span><span class='o'>)</span> <span class='o'>+</span>  
    <span class='nf'>geom_path</span><span class='o'>(</span>show.legend <span class='o'>=</span> <span class='kc'>FALSE</span>, alpha <span class='o'>=</span> <span class='nv'>alpha</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'>coord_equal</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>xlim</a></span><span class='o'>(</span><span class='m'>0</span>, <span class='m'>7</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'><a href='https://rdrr.io/r/graphics/plot.window.html'>ylim</a></span><span class='o'>(</span><span class='o'>-</span><span class='m'>.5</span>, <span class='m'>1.5</span><span class='o'>)</span> <span class='o'>+</span> 
    <span class='nf'>theme_void</span><span class='o'>(</span><span class='o'>)</span>
  <span class='nf'><a href='https://rdrr.io/r/graphics/plot.default.html'>plot</a></span><span class='o'>(</span><span class='nv'>pic</span><span class='o'>)</span>
<span class='o'>&#125;</span>

<span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>male</span> <span class='o'>%&gt;%</span> <span class='nf'>mutate</span><span class='o'>(</span>.frame <span class='o'>=</span> <span class='m'>1</span><span class='o'>)</span>, <span class='m'>1</span><span class='o'>)</span>
</code></pre>
<img src="figs/endstates-1.png" width="700px" style="display: block; margin: auto;" />
<pre class='chroma'><code class='language-r' data-lang='r'><span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>female</span> <span class='o'>%&gt;%</span> <span class='nf'>mutate</span><span class='o'>(</span>.frame <span class='o'>=</span> <span class='m'>100</span><span class='o'>)</span>, <span class='m'>100</span><span class='o'>)</span>
</code></pre>
<img src="figs/endstates-2.png" width="700px" style="display: block; margin: auto;" />

</div>

We're getting closer. Although there is as yet no transition, we have a representation of the two states suitable for tweening, and in my experience that's most of the battle.[^14]

<br>

III. In the flicker of gaslight
-------------------------------

Consciously grasping the idea that "I am transgender" was *hard*. From what I can gather from talking to younger folks, it's not quite the same thing now, and I honestly cannot wrap my head around how the "under 35 set" really think about transgender issues. Don't get me wrong - I admire them and want to share their perspective, but I'm stuck in a much darker place trying to find my way to where they are.[^15]

I was born in 1977. Gender identity disorder was only removed from the DSM in 2013. By way of comparison, homosexuality was removed in 1974. I grew up in a world that was just showing the very beginnings of social acceptance for gay folks, but even so it wasn't until 2017 that gay marriage was legalised. Social change on LGBTIQ issues is slow, and I still live in a world where representations of trans women are dominated by *Rocky Horror Picture Show*, *Silence of the Lambs*, and an endless procession of nameless transgender prostitutes who get killed for no reason and with no explanation.

Oddly enough, none of these stories were what I really wanted to do with my life, so of course I tried to hide my femininity. Of course I didn't say I wanted to be a girl. Of course I didn't let on that I wished I had that body rather than this one. I hid because hiding was rational, and I thought myself a boy because I was *told* I am a boy. And if nothing else, I am *obedient*. I do as I am told, even when I probably should not.

Getting out from under that is hard. My first attempts to grapple with it came while I still lived and identified as a man. It does take a bit of effort for men to discuss feminist topics without sounding like jerks, and while I did an okay job of that (I think) it was hard to think clearly about gender as it pertains to others, when in the back of your head there's this gnawing doubt that *something is wrong* with you. When I tried to verbalise how I felt it came out badly. I didn't know what words to use, and everything I said managed to get everyone angry at me and made me feel weak, fragile and pathetic.

One reason I still struggle so much with oh-so-clever people who "just want to have a rational debate" about whether trans women are really women is that my mental health is not robust to these "debates". Finding any words at all to describe how I feel has been hard. So when I encounter philosophers who want to play [word games with gender](https://arcdigital.media/what-is-gender-identity-10ce0da71999?sk=b86791254b532a296bc0f6861629d3bb), to trap me in some kind of admission that I am a mere caricature of a real woman, all my old fears come flooding back and I lose even the few words that I do have to describe who I am and why I have become her. The depression and self-loathing slides back in, my confidence fades and suicidal thoughts that I had thought long banished reappear. My confusion resurfaces, my sense of my own worth as a human being dissolves... everything just falls apart.

This is not an abstract discussion that is taking place on a level playing field, and I am coldly furious at cisgender people who would play games with our lives.

<br>

Eight. Male to female
---------------------

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nv'>mtf</span> <span class='o'>&lt;-</span> <span class='nf'><a href='https://rdrr.io/pkg/transformr/man/tween_path.html'>tween_path</a></span><span class='o'>(</span><span class='nv'>male</span>, <span class='nv'>female</span>, match <span class='o'>=</span> <span class='kc'>FALSE</span>,
                     ease <span class='o'>=</span> <span class='s'>"cubic-in-out"</span>, nframes <span class='o'>=</span> <span class='m'>100</span>, id <span class='o'>=</span> <span class='nv'>id</span><span class='o'>)</span>

<span class='nv'>animate_mtf</span> <span class='o'>&lt;-</span> <span class='kr'>function</span><span class='o'>(</span><span class='o'>)</span> <span class='o'>&#123;</span>
  <span class='kr'>for</span><span class='o'>(</span><span class='nv'>a</span> <span class='kr'>in</span> <span class='nf'><a href='https://rdrr.io/r/base/seq.html'>seq</a></span><span class='o'>(</span><span class='m'>0</span>,<span class='m'>.5</span>,<span class='m'>.025</span><span class='o'>)</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>mtf</span>, <span class='m'>1</span>, <span class='nv'>a</span><span class='o'>)</span> <span class='c'># fade in</span>
  <span class='kr'>for</span><span class='o'>(</span><span class='nv'>b</span> <span class='kr'>in</span> <span class='m'>1</span><span class='o'>:</span><span class='m'>20</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>mtf</span>, <span class='m'>1</span><span class='o'>)</span> <span class='c'># hold</span>
  <span class='kr'>for</span><span class='o'>(</span><span class='nv'>f</span> <span class='kr'>in</span> <span class='m'>1</span><span class='o'>:</span><span class='m'>100</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>mtf</span>, <span class='nv'>f</span><span class='o'>)</span> <span class='c'># transition</span>
  <span class='kr'>for</span><span class='o'>(</span><span class='nv'>b</span> <span class='kr'>in</span> <span class='m'>1</span><span class='o'>:</span><span class='m'>20</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>mtf</span>, <span class='m'>100</span><span class='o'>)</span> <span class='c'># hold</span>
  <span class='kr'>for</span><span class='o'>(</span><span class='nv'>a</span> <span class='kr'>in</span> <span class='nf'><a href='https://rdrr.io/r/base/seq.html'>seq</a></span><span class='o'>(</span><span class='m'>.5</span>,<span class='m'>0</span>,<span class='o'>-</span><span class='m'>.025</span><span class='o'>)</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>mtf</span>, <span class='m'>100</span>, <span class='nv'>a</span><span class='o'>)</span> <span class='c'># fade out</span>
  <span class='kr'>for</span><span class='o'>(</span><span class='nv'>b</span> <span class='kr'>in</span> <span class='m'>1</span><span class='o'>:</span><span class='m'>20</span><span class='o'>)</span> <span class='nf'>drawframe</span><span class='o'>(</span><span class='nv'>mtf</span>, <span class='m'>100</span>, <span class='m'>0</span><span class='o'>)</span> <span class='c'># hold</span>
<span class='o'>&#125;</span>

<span class='nf'>animate_mtf</span><span class='o'>(</span><span class='o'>)</span>
</code></pre>
<img src="figs/trans1-.gif" width="700px" style="display: block; margin: auto;" />

</div>

<br>

II. Mirror moment
-----------------

That hotel room in Berlin.<br> The terror of putting on the necklace.

The shame of seeing the tears of joy cascading down when you see yourself. The shame of it.

Monster.<br> Pervert.<br> Deviant.<br>

You're not even a real person, are you?<br> Are you going to admit you're just a thing?

Take it off now before anyone sees. Whore.<br> Don't make me get the razor out. <br> You remember how that felt, don't you? <br> You don't want to be a monster, do you? <br>

Why the fuck aren't you taking it off?<br>

<br>

Nine. Stepping forward
----------------------

> The darkness doesn't swallow you. Perhaps that's the strangest part of all. You've seen it swallow other Runners; why doesn't it swallow *you*? Instead, it recedes from your every step. The borderline isn't absolute; quantum fuzziness produces a gradual fade-out, stretching visibility about as far as each extended foot. By day, this is completely surreal, and people have been known to suffer fits and psychotic episodes at the sight of the void's apparent retreat. By night, it seems merely implausible, like chasing an intelligent fog. <br>
>
> -- Greg Egan, *Into Darkness*

As I dig deeper into the internals of R graphics, I encounter more things that I do not understand. The ease with which I can create a beautiful graph using ggplot2 and smoothly animate it with gganimate recedes, and I am left with more puzzles about how the pieces fit together. At this stage I think I understand some of the logic of tweening and have a reasonable grip on the data structures used to represent a ggplot. But as is often the case this deeper understanding has left me with less certainty and confidence in my own skill than I once had. Yet -- having at last resolved the passport dilemma I described earlier -- I have volunteered to give a workshop on this precise topic in [Johannesburg](https://joburg2019.satrdays.org/) in a few months time, and I'm hoping I'm up to the task.[^16]

It strikes me that this is not an unusual scenario. My grasp of the concepts involved is weaker than I would like it to be, yet still I find myself in a position of needing to help others. Whether we are talking about learning statistics with R, about being an academic woman in leadership, serving as an all-too-visible senior trans woman in science, the same pattern arises. In retrospect each action I have taken makes sense, but the next one is always a step into darkness.

<br>

I. Cylon from the beginning?
----------------------------

I have an old, old dream. I had it from as early as I can remember, before I even had a clear grasp on what the word "dream" even meant. Long, long before my dreams were sexualised, before the creepy gross power stuff started appearing, I had this dream. A massive, impenetrable mechanical machine, an array of cogs and gears and things that I don't understand were grinding, whirring away on a production line embedded within a claustrophobic factory. Bodies were passed along the conveyer belt and *things* were done to those bodies. Each time I had the dream my boys body was passed into the machine and it was pulled apart - in a gruesome but oddly bloodless fashion, as though I were a plastic doll - and by some strange magic a girl came out at the end and... this didn't seem strange to me. It felt oddly comforting.

I have no idea whether I should put much weight in this dream. I mean, I've also had recurring dreams of falling, of dying, and yet I haven't fallen and I'm still not dead. Maybe what is more telling than the dream itself is the fact that I have thought about that dream so often, over and over for years. Before I'd heard the word "transgender", before I became caught in this mess that modern gender politics has become. Before all those things, I wanted, thought, felt, obsessed, *dreamed* about the idea of myself as a girl. That, whatever *that* is, was always there. It's what made me want to be friends with the girls. It's what alienated me from the boys.

Does that mean I was "always transgender", even if I didn't verbalise it? I don't know, and I'm not sure that is a helpful way to frame the question. The one thing I can say is that the *thing* that drove me to transition isn't new, and in one form or another there has been something unusual going on for a long time. More than that I cannot say.

<br>

Epilogue. Use of Weapons
------------------------

I have loved the work of Iain M. Banks ever since I was in my teens. My favourite work of his is the 1990 book *Use of Weapons*, which tells the unpleasant story of a mercenary called Cheradenine Zakalwe in two series of interleaved chapters. Starting from a single moment, one series, marked in Roman numerals (X, IX, VII...), goes backwards in time in large steps while the other series (one, two, three...) moves forwards in small ones. Somewhat ambitiously, I've mirrored that structure here.

I think about that book a lot because throughout my own life, I have often felt like nothing so much as a person expected to become a *weapon*. Reading Andrea Dworkin's amazing and distressing book *Woman Hating* (1974), it's hard not to come away with the view that we live in a world in which women are treated as *possessions*, and as she puts it

> A precise corollary of possession is prostitution. The prostitute, the woman as object, is defined by the usage to which the possessor puts her

The book doesn't explicitly talk about what men are, but when I read it all I could think of are the countless examples of *admirable* male violence that I too was expected to perform, the aggressiveness and competitiveness that I too was supposed to display, and of how severely I was punished when I recoiled in disgust from my assigned role. Patriarchy makes women into possessions and men into weapons - neither role is particularly liberating, but there's a hierarchy there that is not exactly subtle.

What then does it say about me, a transsexual woman? What am I and where do I fit in this structure? Andrea Dworkin's answer to the question is as follows:

> There is no doubt that in the culture of male-female discreteness, transsexuality is a disaster for the individual transsexual. Every transsexual, white, black, man, woman, rich, poor, is in a state of primary emergency (see p. 185) as a transsexual. There are 3 crucial points here. One, every transsexual has the right to survival on his/her own terms. That means that every transsexual is entitled to a sex-change operation, and it should be provided by the community as one of its functions. This is an emergency measure for an emergency condition. Two, by changing our premises about men and women, role-playing, and polarity, the social situation of transsexuals will be transformed, and transsexuals will be integrated into community, no longer persecuted and despised. Three, community built on androgynous identity will mean the end of transsexuality as we know it. Either the transsexual will be able to expand his/her sexuality into a fluid androgyny, or, as roles disappear, the phenomenon of transsexuality will disappear and that energy will be transformed into new modes of sexual identity and behavior.

I don't know how to feel about this. On first reading, it's rather nice to read something for a change in which a radical feminist *doesn't* call me the monstrous violent thing that I've so desperately tried to flee from my whole life. Her assertion that "every transsexual is in a state of primary emergency" is perhaps not as true now in 2019 than it was in 1974, at least to the extent that in recent years we have seen transgender people integrated into the community, our identities destigmatised. But the change has been rapid. The world I grew up in is the one Dworkin describes, and the suicidality, disorientation and terror I have felt for most of my life does feel rather like "a primary emergency". I have on occasions been forced to detransition briefly, and the feeling is *horrifying*. Having at last experienced what it's like to look in the mirror and see someone I recognise as myself I have such an overwhelming feeling of disgust and loathing when I see *that man*. I'm not sure if I'm exaggerating when I say I'd rather die than detransition. That particular bridge is well and truly burned.

What puzzles me, a little, is whether I agree with Dworkin's more speculative claim, namely that in a community built around androgynous identity, the phenomenon of transsexuality will disappear. I honestly don't know. My intuitions aren't any better than any else's on this point, because the world that we currently live in is so *completely* gendered from top to bottom, that I am deeply skeptical that any of us have good intuitions about what that kinder world would be like.

A second puzzle is that increasingly I find myself transformed into a different kind of weapon, thankfully a purely rhetorical one. Why does Dworkin feel she even *needs* to answer the question of whether transsexuality would exist in an androgynous utopia? If Julia Serano's (2007) notion of "subconscious sex" has anything like the biological basis that she suggests, there would probably still be transsexual people in an androgynous world, it's just that we would no longer be particularly interesting. It would hardly undermine Dworkin's main point if transsexuality survived even after gender is gone. So why is the stronger claim -- ignoring the weasel words "as we know it" that seem quite uncharacteristic of her writing style in general -- even necessary?

My guess is that this is because in the world we currently inhabit, cisgender writers and politicians find us *useful* as rhetorical devices. Consider Cordelia Fine's (2010) book, *Delusions of Gender*. It's primarily a book about the scientific foundations of biological sex differences between (cisgender) men and women, yet she opens the book with a quote by a trans woman:

> The more I was treated as a woman, the more woman I became. I adapted willy-nilly. If I was assumed to be incompetent at reversing cars, or opening bottles, oddly incompetent I found myself becoming. If a case was thought too heavy for me, inexplicably I found it so myself
>
> -- Jan Morris, a male to female transsexual

Why is a trans woman's musing the best testimonial here? Suffice it to say, Jan Morris doesn't in fact reappear much in Fine's book, and as far as I can tell the only other transgender person to feature is the neuroscientist Ben Barres, and he is included primarily to tell an anecdote about his experiences as a trans man. *Delusions of Gender* has little use for transgender people, except to tell quaint stories that the (presumed cisgender woman) reader will find convenient. We make terribly good anecdotes for people to tell stories that don't actually involve us.[^17]

As a second example, the book I am currently reading is [*Rage Becomes Her*](https://www.simonandschuster.com/books/Rage-Becomes-Her/Soraya-Chemaly/9781501189555) by Soraya Chemaly. It is an *excellent* book and I am enjoying it a great deal. It talks a lot about how boys (and men) are socialised to express anger while girls (and women) are not, and how this places women at a disadvantage in our society. For the most part I tend to agree with her argument, but I think it doesn't have a lot to say about trans and gender nonconforming folks. That's not to say she neglects the topic, of course (as I say, it's a very good book), but we're a little inconvenient for telling *any* clean story about gender socialisation. There's one passage early on that discusses us...

> I have focused on binary gender descriptions because there is very little research about childhood, emotional regulation, and gender fluidity, and because we do not, as a culture, have social "scripts"---the unconscious guidelines we follow to organize thoughts and behavior---for nonbinary people. Almost all studies use traditional binary frameworks for analysis. There are few positive dominant stereotypes about bi, trans, and queer people that shape childhood. Children who defy binaries are caught in the crosshairs, leaving parents to either create safe environments and force social change, or else contribute, wittingly or not, to damaging demands that their children conform.

She quotes Julia Serano here,

> "I find that those who wish to ridicule or dismiss me," trans activist Julia Serano has explained, "do not simply take me to task for the fact that I fail to conform to gender norms. Instead, more often than not, they mock my femininity. From my perspective, most of the anti-trans sentiment that I have had to deal with is probably better described as misogyny."

and then immediately the book pivots back to (implicitly cisgender) girls.

> It's a cruel trick we play on girls, exposing them to these realities at the same time that we exert the most social pressure on them to ignore and hide the anger they provoke.

This passage is striking, because as a trans woman myself I remember that quote from the start of Julia Serano's [*Whipping Girl*](https://en.wikipedia.org/wiki/Whipping_Girl) quite vividly. Of particular note, here is the preceding sentence as it appears in the original work.

> I was sometimes teased for being different, for being an typical or unmasculine boy, but it was nothing compared to the venom that was reserved for those boys who acted downright feminine.

This was my experience also -- and again, I should note that Chemaly does comment on the mistreatment of feminine boys! -- and as I have transitioned and started to pass as a cisgender woman, I experience *less* violence than I did whenever I revealed myself as a feminine boy. This does not fit cleanly with the stories we are told about how girls and boys are socialised, not unless we are also willing to be honest about the sheer scale of the transmisogynistic violence that forms the a large part of the socialisation for many feminine boys.[^18]

I do get a little sad though. What of our anger? What of our fury? How does a trans woman express rage when the moment we do so it will call our very identities into question? We don't merely become the Hysterical Woman when we speak up, we become Crazy Trannies, perverted men in women's clothing. As long as we remain silent and docile, our stories make convenient copy. It seems to me that we become less convenient once we speak in our own voices.

And so I worry, even still. For me to be useful as rhetorical weapon, must I continue to play out the role of The Good Tran? I need a suitably sad backstory, a tale of redemption and growth as a transgender woman. Without that I'm not much use at all, am I? And if transgender women are not useful to you, I wonder, what will become of us?

<br><br><br>

[^1]: Sigh. I wrote this essay at the start of the program, and while I will stand by my original decision not to talk about specifics, my experiences later in the program left me a little less kindly disposed to it than I was when I wrote the original piece.

[^2]: In retrospect, I think this section was far too charitable to men. Since that time I've had intimate relationships with a few men as a trans woman, and while some of those experiences have been lovely (well, more than lovely actually...), others have been nothing short of abusive. I have to say that my opinion of men has declined *considerably*, even from the admittedly low baseline view I started with. There are few things in this life that have terrified me more than seeing a man exploding in violent rage because a *tranny* had dared to speak back at him. Being treated as a fetish object by men is one thing; being the target of their untempered rage when their shameful little fuck toy turns out to have a mind of her own is quite another.

[^3]: One omission that strikes me as salient now is that there is a subtle difference in how I experience these things to how cis women do. In the last two years I've learned a lot about how to make certain that I "pass" as a woman, and I'm much better at it now than I was then. That has come at a price, however. As men have become more emboldened to treat me in the same misogynistic way they treat cis women, the more terrified I have become at the prospect of one of them realising what I am. I've seen too many men explode in anger and disgust when they realise they've been flirting with a trans woman to take risks. Even more so than cis women, I cannot risk pushing back against it when men treat me in this demeaning fashion. To such a man I am not merely a "bitch" if I speak up for myself, I am an *abomination*, and they react accordingly.

[^4]: In the two years since I wrote this my feelings on this matter have become considerably more bitter, though slightly more nuanced. On the nuanced side I've noticed that this phenomenon is not universal: among communities where the pernicious effects of misogyny are better recognised, this has not been quite so pronounced. I have *not* experienced this loss of credibility in the R community, for example, but it has been very noticeable in my interactions with the self-styled "open science" community in psychology. On the bitter side, the fact that this pattern continued to get worse over the years has led to quite a lot of conflict. My opinions of the open science community in psychology have deteriorated to the point that in 2021 I [formally renounced](https://twitter.com/djnavarro/status/1377369416560611329) an award that had been given to my by the Society for the Improvement of Psychological Science in 2019. I will not waste my time on people who do not take me seriously when I have so many other options for how to live my life.

[^5]: These days I find that women are much more willing to talk to me and share that part of their world, and I am deeply grateful. In part, I have found it reassuring to learn how many of my own experiences are mirrored in theirs, but perhaps more importantly the advice I've been given through the whisper net *has* kept me safe in many situations that might otherwise have been... quite bad.

[^6]: I honestly cannot believe how naive I was when I wrote this. In the last couple of years I think we've seen the mask come off the TERF movement: as they've achieved more political wins in their activism, particularly in the UK, they've become openly hateful now. There's barely even a pretense that their political goals are based in anything other than a desire to punish trans women. In the last two years we've seen their views become normalised, and the dehumanising rhetoric targeting trans women has become so much more grotesque.

[^7]: Jesse Singal, obviously. In the two years since I wrote the original piece I think it's become clearer to many others that he is an entirely untrustworthy source when it comes to trans women, but back in 2019 very few people in my academic community listened to me when I tried to speak about how badly slanted his journalism on transgender subjects is. I am still bitter about that.

[^8]: Looking back, one thing I find striking about this section is that back in 2019 I was too timid to name the specific person I was upset with when I wrote this: [Chimamanda Ngozie Adichie](https://www.vox.com/identities/2017/3/15/14910900/chimamanda-ngozi-adichie-transgender-women-comments-apology). In an interview with BBC in 2017, when asked about whether trans women have a role in feminism, she said the following: *"When people talk about 'are trans women women?', my feeling is 'trans women are trans women'. If you've lived in the world as a man with the privileges the world accords to men and then switch gender, it's difficult for me to accept that we can equate your experience with the experience of a woman who has lived from the beginning in the world as a woman and who has not been accorded those privileges that men are"*. Suffice it to say I think these remarks border on transmisogyny and, quite frankly, show a remarkable lack of knowledge of what trans women's lives are actually like (and no, I do not think very much of her [apology](https://www.facebook.com/chimamandaadichie/photos/a.469824145943.278768.40389960943/10154893542340944/?type=3&theater) -- all she's doing there is reasserting her original claim). Personally, I would never have the arrogance to comment on the lives of Black women, nor would I have the gall to opine on what status should be accorded to the voices of Black women in feminist discussion. On matters of race I have little to say: I try to stay in my lane on such subjects. Along the same lines, I think it would be wise if cisgender women were to do likewise when it comes to commenting on the ostensible *privileges* that trans women are accorded. My advice for any and all cis women tempted to comment on male privilege as it pertains to trans women would be: *don't*. You stay in your lane and I'll stay in mine.

[^9]: I can't remember where I heard this, but at some point after I wrote this essay I came across this expression: *If you want to know what a man thinks of cis women in private, look at how he treats trans women in public*. It seems apt.

[^10]: To be more precise, because my original phrasing here isn't ideal, while I *did* have that fear, I didn't take that fear seriously because I'd been conditioned to believe that rape doesn't happen to people like me. I thought I was being irrational to worry about it, so I ignored my fears. To my own detriment, as it turned out.

[^11]: In the original version of the essay I linked here to an essay called *Valentines Day*, which was the first time I'd ever publicly admitted that I'd been raped in my 20s. That essay is now gone (it's a little too raw for me to face those words), but I did later write a different [essay](/post/something-improbable-happened/) in which I tried to come to terms with the experience.

[^12]: Rereading the essay in 2021 I can't help but notice how often I resort to overtly transmisogynistic language when describing myself. There's quite a lot of unexamined self-loathing in how I wrote this piece. I would *never* describe another trans woman using the language I direct at myself in this essay. It's cruel and dehumanising. That kind of self-hate is something I've been working on since then.

[^13]: I later wrote about that feeling and some of the associated fears [here](/post/daniel/).

[^14]: In the original 2019 version of this post, the "male" and "female" states were rendered as filled polygons with holes using [`geom_polypath()`](https://rdrr.io/pkg/ggpolypath/man/geom_polypath.html), as was the final MTF animation. As a consequence of the changes to the packages in the last two years, I decided to revert to a version that used [`tween_path()`](https://rdrr.io/pkg/transformr/man/tween_path.html) to compute the intermediate states and rendered frames using `geom_path()`. Sigh. If I'd known more about computational reproducibility back then I could probably have written code that would be a little more robust to this issue, but such is life.

[^15]: It is hard to understate how different the world was when I grew up, and what the attitudes towards gender nonconformity and transsexuality were like when I was a child. I still don't know how to put into words how frightened I was. You can see some of that emotion come out occasionally on [twitter](https://twitter.com/djnavarro/status/1373802733522796545), but it doesn't do justice to what the actual experience was.

[^16]: Sigh. As it turns out, I wasn't. I had a severe panic attack while I was there, and it was the beginning of one of the darkest periods in my life. I burned out badly and had to take months off work to deal with the mental health problems that ensued. The fallout from that part of my life still hasn't ended, I am sorry to say.

[^17]: This is another case where I have become more cynical. I've seen her name appear several times in documents that express support for "gender critical feminism", which is little more than a polite name for "anti-trans feminism". Though this footnote is hardly the place to make the case, my opinions on the book have become more negative and I no longer think that Fine's treatment of trans people in that book was accidental.

[^18]: Two years later I still stand by this. I've experienced a lot more of the violence that women have to deal with and none of it has changed my mind about this point: many feminists have a very poor grasp of how unremittingly violent "male socialisation" is for feminine boys, and have a tendency to say very silly things about their lives as a consequence. It has become my view that if you haven't had the personal experience of taking a beating for displaying the slightest sign of femininity, you would be *very* ill-advised to try to speculate about how feminine boys are socialised.

