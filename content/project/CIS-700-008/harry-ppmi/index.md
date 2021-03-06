---
title: Share my new passion for a vibrant new ecosystem Harry Potter Fan Fiction
summary: A small snippet of my paper, some initial analysis between Harry Potter Fanfiction and the original canons.
tags:
- CIS 700-008
date: "2016-05-04T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: "Harry Potter and The Prisoner of Azkaban"
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/tensorglow
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

---


<html xmlns="https://www.w3.org/1999/xhtml" lang="" xml:lang="">
<head>
  <meta charset="utf-8" />
  <meta name="generator" content="pandoc" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes" />
  <title>harry-ppmi</title>
  <style>
    code{white-space: pre-wrap;}
    span.smallcaps{font-variant: small-caps;}
    span.underline{text-decoration: underline;}
    div.column{display: inline-block; vertical-align: top; width: 50%;}
    div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
    ul.task-list{list-style: none;}
  </style>
  <!--[if lt IE 9]>
    <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv-printshiv.min.js"></script>
  <![endif]-->
</head>
<body>
<h1 id="preliminary-results">Preliminary Results</h1>
<p>The following is an example of an event chain extracted from a story from the fan fiction:</p>
<ol>
<li><p>(’CLUSTER 0’, ’nsubj’), (’walked’, ’root’)</p></li>
<li><p>(’CLUSTER 0’, ’nsubj’), (’looked’, ’root’)</p></li>
<li><p>(’CLUSTER 0’, ’nsubj’), (’changed’, ’root’)</p></li>
<li><p>(’CLUSTER 0’, ’nsubj’), (’asked’, ’root’)</p></li>
</ol>
<p>In the example above, the character in Harry Potter referred to as ’CLUSTER 0’ first walks, then looks, changes, and finally asks. The first element in every tuple is the word in the document with its replaced coreference-resolution tag and the second element is its first order dependency parse that was used to extract the event chain of every noun subject of a story.</p>
<h1 id="results">Results</h1>
<h2 id="pointwise-mutual-information-pmi-analysis">Pointwise Mutual Information (PMI) Analysis</h2>
<p>The most probable bigrams and the bigrams with the highest PMI were ran over all words, verbs, and events of the two corporas: Harry Potter Fanfiction and Harry Potter Canons. PMI analysis reveals the unique co-occuring concepts in each of the corporas and highlights other stylistic writing differences on average from the authors. Most probable bigrams are shown along side the highest PMI bigrams in each of the tables to show that the magnitude of the frequency count of each bigram over total bigrams does not entail importance or significance in a document and underscoring the value of PMI analysis.</p>
<div id="long">
<table>
<caption>PMI Analysis on Words.<span id="long" label="long">[long]</span></caption>
<tbody>
<tr class="odd">
<td style="text-align: center;">Harry Potter Fanfiction</td>
<td style="text-align: center;">Harry Potter Canon</td>
<td style="text-align: center;">Harry Potter Fanfiction</td>
<td style="text-align: center;">Harry Potter Canon</td>
</tr>
<tr class="even">
<td style="text-align: center;">of the</td>
<td style="text-align: center;">of the</td>
<td style="text-align: center;">bibbidi bobbidi</td>
<td style="text-align: center;">avada kedavra</td>
</tr>
<tr class="odd">
<td style="text-align: center;">in the</td>
<td style="text-align: center;">in the</td>
<td style="text-align: center;">merus lumens</td>
<td style="text-align: center;">felix felicis</td>
</tr>
<tr class="even">
<td style="text-align: center;">to the</td>
<td style="text-align: center;">said harry</td>
<td style="text-align: center;">zauberei dorf</td>
<td style="text-align: center;">bertha jorkins</td>
</tr>
<tr class="odd">
<td style="text-align: center;">it was</td>
<td style="text-align: center;">he was</td>
<td style="text-align: center;">hoity toity</td>
<td style="text-align: center;">whomping willow</td>
</tr>
<tr class="even">
<td style="text-align: center;">on the</td>
<td style="text-align: center;">at the</td>
<td style="text-align: center;">palatino linotype</td>
<td style="text-align: center;">expecto patronum</td>
</tr>
<tr class="odd">
<td style="text-align: center;">at the</td>
<td style="text-align: center;">to the</td>
<td style="text-align: center;">magikos akademia</td>
<td style="text-align: center;">dressing gown</td>
</tr>
<tr class="even">
<td style="text-align: center;">he was</td>
<td style="text-align: center;">on the</td>
<td style="text-align: center;">alarte ascendare</td>
<td style="text-align: center;">grubbly plank</td>
</tr>
<tr class="odd">
<td style="text-align: center;">to be</td>
<td style="text-align: center;">it was</td>
<td style="text-align: center;">inkosi inkosikazi</td>
<td style="text-align: center;">zacharias smith</td>
</tr>
<tr class="even">
<td style="text-align: center;">she was</td>
<td style="text-align: center;">he had</td>
<td style="text-align: center;">namby pamby</td>
<td style="text-align: center;">law enforcement</td>
</tr>
<tr class="odd">
<td style="text-align: center;">i was</td>
<td style="text-align: center;">out of</td>
<td style="text-align: center;">modus operandi</td>
<td style="text-align: center;">auntie muriel</td>
</tr>
<tr class="even">
<td style="text-align: center;">and i</td>
<td style="text-align: center;">said ron</td>
<td style="text-align: center;">cuevas gontan</td>
<td style="text-align: center;">bathilda bagshot</td>
</tr>
<tr class="odd">
<td style="text-align: center;">out of</td>
<td style="text-align: center;">into the</td>
<td style="text-align: center;">füvessy uram</td>
<td style="text-align: center;">goal posts</td>
</tr>
<tr class="even">
<td style="text-align: center;">going to</td>
<td style="text-align: center;">to be</td>
<td style="text-align: center;">toothflossing stringmints</td>
<td style="text-align: center;">pansy parkinson</td>
</tr>
<tr class="odd">
<td style="text-align: center;">with a</td>
<td style="text-align: center;">in a</td>
<td style="text-align: center;">babbitty rabbitty</td>
<td style="text-align: center;">deathly hallows</td>
</tr>
<tr class="even">
<td style="text-align: center;">he had</td>
<td style="text-align: center;">from the</td>
<td style="text-align: center;">higgledy piggledy</td>
<td style="text-align: center;">phineas nigellus</td>
</tr>
<tr class="odd">
<td style="text-align: center;">as he</td>
<td style="text-align: center;">said hermione</td>
<td style="text-align: center;">dawh dawh</td>
<td style="text-align: center;">king’s cross</td>
</tr>
<tr class="even">
<td style="text-align: center;">in a</td>
<td style="text-align: center;">had been</td>
<td style="text-align: center;">shoop shoop</td>
<td style="text-align: center;">diagon alley</td>
</tr>
<tr class="odd">
<td style="text-align: center;">for the</td>
<td style="text-align: center;">he said</td>
<td style="text-align: center;">loundon’s towne</td>
<td style="text-align: center;">pumpkin juice</td>
</tr>
<tr class="even">
<td style="text-align: center;">was a</td>
<td style="text-align: center;">was a</td>
<td style="text-align: center;">farlin flookey</td>
<td style="text-align: center;">st mungos</td>
</tr>
<tr class="odd">
<td style="text-align: center;">as she</td>
<td style="text-align: center;">of his</td>
<td style="text-align: center;">helter skelter</td>
<td style="text-align: center;">godrics hollow</td>
</tr>
<tr class="even">
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>
</div>
<p>Two random variable X, Y are independent iff their joint distribution is equal to the product of their marginal probabilities: <br /><span class="math display"><em>p</em>(<em>X</em>, <em>Y</em>) = <em>p</em>(<em>X</em>)<em>p</em>(<em>Y</em>)</span><br /> That is for all outcomes x, y: <br /><span class="math display"><em>p</em>(<em>X</em>, <em>Y</em>) = <em>p</em>(<em>X</em>)<em>p</em>(<em>Y</em>)</span><br /> So the mutual information "I" can be described as: <br /><span class="math display">$$I(X; Y ) = 
\sum_{XY}^{}
p(X = x, Y = y) log p(X = x, Y = y)
p(X = x)p(Y = y)$$</span><br /> We find pairs of words <em>wi, wj</em> that have high pointwise mutual information, because this signifies the frequency count of their co-occurrence is much greater than how often each word appeared independently in the corpora, as seen in equation 4. <br /><span class="math display">$$PMI(wi, wj ) = log\tfrac{p(wi, wj )}{p(wi)p(wj )}$$</span><br /></p>
<p>In Table 1, you can see that the most probable bigrams aren’t telling, but both the Canon and the Fanfiction feature common ’spells’ from the text as their highest rated PMI bigrams. From the canon you see ’avada kedavra’ and ’expecto patronum’ which were common spells from the books and films, and from the Fanfiction we see ’merus lumens’ and ’alarte ascendare.’</p>
<div id="long">
<table>
<caption>PMI Analysis on Verbs.<span id="long" label="long">[long]</span></caption>
<tbody>
<tr class="odd">
<td style="text-align: center;">Harry Potter Fanfiction</td>
<td style="text-align: center;">Harry Potter Canon</td>
<td style="text-align: center;">Harry Potter Fanfiction</td>
<td style="text-align: center;">Harry Potter Canon</td>
</tr>
<tr class="even">
<td style="text-align: center;">said said</td>
<td style="text-align: center;">said said</td>
<td style="text-align: center;">oyt cafru</td>
<td style="text-align: center;">slammed shut</td>
</tr>
<tr class="odd">
<td style="text-align: center;">let go</td>
<td style="text-align: center;">said looking</td>
<td style="text-align: center;">Erised oyt</td>
<td style="text-align: center;">starting feel</td>
</tr>
<tr class="even">
<td style="text-align: center;">know said</td>
<td style="text-align: center;">do said</td>
<td style="text-align: center;">born dies</td>
<td style="text-align: center;">looking saw</td>
</tr>
<tr class="odd">
<td style="text-align: center;">said looking</td>
<td style="text-align: center;">know said</td>
<td style="text-align: center;">doo doo</td>
<td style="text-align: center;">trying sound</td>
</tr>
<tr class="even">
<td style="text-align: center;">was was</td>
<td style="text-align: center;">said know</td>
<td style="text-align: center;">destroyed destroyed</td>
<td style="text-align: center;">came striding</td>
</tr>
<tr class="odd">
<td style="text-align: center;">go said</td>
<td style="text-align: center;">got said</td>
<td style="text-align: center;">cha cha</td>
<td style="text-align: center;">came hurrying</td>
</tr>
<tr class="even">
<td style="text-align: center;">do said</td>
<td style="text-align: center;">I’ve got</td>
<td style="text-align: center;">de gnome</td>
<td style="text-align: center;">looking puzzled</td>
</tr>
<tr class="odd">
<td style="text-align: center;">have do</td>
<td style="text-align: center;">was said</td>
<td style="text-align: center;">drip drip</td>
<td style="text-align: center;">looking relieved</td>
</tr>
<tr class="even">
<td style="text-align: center;">get said</td>
<td style="text-align: center;">is said</td>
<td style="text-align: center;">tick tick</td>
<td style="text-align: center;">looking bewildered</td>
</tr>
<tr class="odd">
<td style="text-align: center;">said know</td>
<td style="text-align: center;">said looked</td>
<td style="text-align: center;">beep beep</td>
<td style="text-align: center;">turned face</td>
</tr>
<tr class="even">
<td style="text-align: center;">have said</td>
<td style="text-align: center;">said was</td>
<td style="text-align: center;">won won</td>
<td style="text-align: center;">trying catch</td>
</tr>
<tr class="odd">
<td style="text-align: center;">said looked</td>
<td style="text-align: center;">go said</td>
<td style="text-align: center;">captivate resonating</td>
<td style="text-align: center;">managed find</td>
</tr>
<tr class="even">
<td style="text-align: center;">knew was</td>
<td style="text-align: center;">have said</td>
<td style="text-align: center;">click click</td>
<td style="text-align: center;">supposed be</td>
</tr>
<tr class="odd">
<td style="text-align: center;">asked said</td>
<td style="text-align: center;">said think</td>
<td style="text-align: center;">live born</td>
<td style="text-align: center;">stopped talking</td>
</tr>
<tr class="even">
<td style="text-align: center;">know is</td>
<td style="text-align: center;">said got</td>
<td style="text-align: center;">liked hated</td>
<td style="text-align: center;">wanted talk</td>
</tr>
<tr class="odd">
<td style="text-align: center;">know know</td>
<td style="text-align: center;">see said</td>
<td style="text-align: center;">vested pronounce</td>
<td style="text-align: center;">made feel</td>
</tr>
<tr class="even">
<td style="text-align: center;">know do</td>
<td style="text-align: center;">get said</td>
<td style="text-align: center;">raptured ends</td>
<td style="text-align: center;">stood waiting</td>
</tr>
<tr class="odd">
<td style="text-align: center;">have go</td>
<td style="text-align: center;">asked said</td>
<td style="text-align: center;">ceases amaze</td>
<td style="text-align: center;">expecting see</td>
</tr>
<tr class="even">
<td style="text-align: center;">see said</td>
<td style="text-align: center;">’s said</td>
<td style="text-align: center;">bid adieu</td>
<td style="text-align: center;">let go</td>
</tr>
<tr class="odd">
<td style="text-align: center;">want know</td>
<td style="text-align: center;">think said</td>
<td style="text-align: center;">loved hated</td>
<td style="text-align: center;">need talk</td>
</tr>
<tr class="even">
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>
</div>
<p>The difference between unique co-occuring verbs between the fanfiction and the canon is telling. One of the conclusions we can draw from the results of the PMI analysis of co-occuring verbs is writing style difference. There are 4 main writing styles: Expository, Descriptive, Persuasive, and Narrative. The co-occuring verbs that were identified as the highest-valued unique concepts in the fanfiction (3rd column from the left) reveal a certain writing style that is most in common with ’Descriptive’ and the Canon (last column in Table 2) is most in common with ’Narrative.’ In a descriptive writing style, the authors on average use language that lead by the five senses (what they hear, see, smell, taste, or touch), which is evidence by the "drip, drip" and "beep, beep" and "tick, tick" ranking amongst the highest PMI bigrams for this corpora. By contrast, narrative style of writing is concerned with character development, constructing a story, conflict and setting, which is evidenced by the pleasant flow of co-occurring verbs in the canon.</p>
<div id="long">
<table>
<caption>PMI Analysis on Events.<span id="long" label="long">[long]</span></caption>
<tbody>
<tr class="odd">
<td style="text-align: center;">Harry Potter Fanfiction</td>
<td style="text-align: center;">Harry Potter Canon</td>
<td style="text-align: center;">Harry Potter Fanfiction</td>
<td style="text-align: center;">Harry Potter Canon</td>
</tr>
<tr class="even">
<td style="text-align: center;">(was, gone)</td>
<td style="text-align: center;">(wanted, watch)</td>
<td style="text-align: center;">(acknowledged, manifested)</td>
<td style="text-align: center;">(woke, remember)</td>
</tr>
<tr class="odd">
<td style="text-align: center;">(love, hear)</td>
<td style="text-align: center;">(watch, was)</td>
<td style="text-align: center;">(orgasimed, griping)</td>
<td style="text-align: center;">(sleep, dozed)</td>
</tr>
<tr class="even">
<td style="text-align: center;">(drifted, sleep)</td>
<td style="text-align: center;">(was, rose)</td>
<td style="text-align: center;">(clamp, her mouth)</td>
<td style="text-align: center;">(fuming, hear)</td>
</tr>
<tr class="odd">
<td style="text-align: center;">(turned, walked)</td>
<td style="text-align: center;">(rose, pressed)</td>
<td style="text-align: center;">(streaking, ripple)</td>
<td style="text-align: center;">(check, chose)</td>
</tr>
<tr class="even">
<td style="text-align: center;">(love, know)</td>
<td style="text-align: center;">(pressed, blinked)</td>
<td style="text-align: center;">(sed, shuld)</td>
<td style="text-align: center;">(clambered, hurried)</td>
</tr>
<tr class="odd">
<td style="text-align: center;">(want, know)</td>
<td style="text-align: center;">(rolled, fell)</td>
<td style="text-align: center;">(hace, xplained)</td>
<td style="text-align: center;">(hurried, tell)</td>
</tr>
<tr class="even">
<td style="text-align: center;">(walked, left)</td>
<td style="text-align: center;">(fell, woke)</td>
<td style="text-align: center;">(contunue, document)</td>
<td style="text-align: center;">(living, giving)</td>
</tr>
<tr class="odd">
<td style="text-align: center;">(knew, was)</td>
<td style="text-align: center;">(woke, remember)</td>
<td style="text-align: center;">(clanged, aperating)</td>
<td style="text-align: center;">(squeezed, could)</td>
</tr>
<tr class="even">
<td style="text-align: center;">(hope, enjoyed)</td>
<td style="text-align: center;">(was, heaving)</td>
<td style="text-align: center;">(reinforced, quenched)</td>
<td style="text-align: center;">(crumpled, burned)</td>
</tr>
<tr class="odd">
<td style="text-align: center;">(was, be)</td>
<td style="text-align: center;">(slumped, fell)</td>
<td style="text-align: center;">(differ, a bushy - haired girl)</td>
<td style="text-align: center;">(avoid, hitting)</td>
</tr>
<tr class="even">
<td style="text-align: center;">(turned, left)</td>
<td style="text-align: center;">(looking, felt)</td>
<td style="text-align: center;">(rejuvenated, cleansed)</td>
<td style="text-align: center;">(hitting, groped)</td>
</tr>
<tr class="odd">
<td style="text-align: center;">(knew, be)</td>
<td style="text-align: center;">(felt, was)</td>
<td style="text-align: center;">(delves, submerges)</td>
<td style="text-align: center;">(groped, smashed)</td>
</tr>
<tr class="even">
<td style="text-align: center;">(would, like)</td>
<td style="text-align: center;">(felt, fainted)</td>
<td style="text-align: center;">(punishing, pine)</td>
<td style="text-align: center;">(fighting, keep)</td>
</tr>
<tr class="odd">
<td style="text-align: center;">(be, was)</td>
<td style="text-align: center;">(lay, looking)</td>
<td style="text-align: center;">(oohed, ahhed)</td>
<td style="text-align: center;">(know, meeting)</td>
</tr>
<tr class="even">
<td style="text-align: center;">(like, know)</td>
<td style="text-align: center;">(looking, sleep)</td>
<td style="text-align: center;">(memorised, visualised)</td>
<td style="text-align: center;">(meeting, holding)</td>
</tr>
<tr class="odd">
<td style="text-align: center;">(know, was)</td>
<td style="text-align: center;">(sleep, dozed)</td>
<td style="text-align: center;">(dk, the little blue box)</td>
<td style="text-align: center;">(agrees, sent)</td>
</tr>
<tr class="even">
<td style="text-align: center;">(try, update)</td>
<td style="text-align: center;">(been, realized)</td>
<td style="text-align: center;">(proceeds, doodle)</td>
<td style="text-align: center;">(throws, getting)</td>
</tr>
<tr class="odd">
<td style="text-align: center;">(left, left)</td>
<td style="text-align: center;">(wrenched, leaving)</td>
<td style="text-align: center;">(infatuated, unbelieving)</td>
<td style="text-align: center;">(getting, rid)</td>
</tr>
<tr class="even">
<td style="text-align: center;">(hope, liked)</td>
<td style="text-align: center;">(leaving, standing)</td>
<td style="text-align: center;">(releases, vanishes)</td>
<td style="text-align: center;">(go, turned)</td>
</tr>
<tr class="odd">
<td style="text-align: center;">(had, was)</td>
<td style="text-align: center;">(standing, staring)</td>
<td style="text-align: center;">(bowing, restoring)</td>
<td style="text-align: center;">(cleared, read)</td>
</tr>
<tr class="even">
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>
</div>
<p>In Table 3, an event was considered co-occuring if it occurred alongside another event in the same story and in the same chapter. Events were extracted first using dependency parsing and semantic role labeling in conjunction with coreference resolution. Each event consisted of a tuple with one verb and one argument (whether subject or object) and counted over the whole corpora. The events here are not character dependent, this is an analysis over all the events found in the corpora in general. Future work will include PMI analysis over co-occuring events within each character to delineate not only events that correspond to each character, but which events consititute a unique concept to that character. These general results will also be applied in the future work as positive examples for predicitive modeling to predict an event given a previous event and/or it’s temperal order.</p>
</body>
</html>