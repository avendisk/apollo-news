+++
title = "20191030_issue4"
date = 2024-09-03T16:16:44-04:00
draft = true
featured_image = "imgs/feature.png"
featured_image_caption = "feature caption"

[params]
    paper_title = "Apollo News"
    actual_date = 2024-09-03T16:16:44-04:00
    issue_num = 1
+++

<!-- you can put percent signs on this instead of <> to process markdown -->
{{< begin-page >}}
{{< paper-heading >}}

{{< main-article >}}
<!-- The main english article should not be more than 740 characters -->
<!-- The main japanese article should not be more than 350 characters -->
<h2> INSERT_ARTICLE_TITLE_HERE </h2>
{{< author name="INSERT_AUTHOR_NAME_HERE" >}}

On October 12th, Typhoon Hagibis (Typhoon 19) hit Japan. Flooding happened all over Soma. Both of the main rivers in Soma, Koizumi and Uta flooded. Around one quarter of the buildings in Soma flooded. Most of Soma lost water for one week. In the Soma area 21,000 people suffered from the water outage.  Only two weeks later there were heavy rains. The rains flooded more parts of the town. With the rains on the 25th and the typhoon on the 12th, a total of more than 3700 buildings were flooded. Now most of Soma is recovering but it will take a long time to be complete. 

{{< /main-article >}}

![Road washout in Soma](imgs/floodsoma.jpg)
{.feature-img}

{{< articles/custom-article >}}
<!-- a quarter article should not be more than 600 char -->
<h2>Review: REVIEW_TITLE</h2>
{{< author name="INSERT_AUTHOR_NAME_HERE" >}}

<!-- Change the Ramen rating number to be the number out of five -->
{{< articles/ramen-ratings 3 >}}

{{< /articles/custom-article >}}



{{< quarter-article markdownify >}}
## Useful Phrase
### “INSERT PHRASE HERE”

**Meaning:**
**When to use:** 
**Who to use with:** 
**How to respond:** 


**Example conversation:**  
**Peter:**
**Mary:** 
**Peter:** 
{{< /quarter-article >}}


{{% difficult-words %}}
<!-- max number of difficult words is 10 -->

* greet
* 挨拶する 

* useful
* 便利な；有用な  

* wild
* 荒っぽい；野生



{{% /difficult-words %}}
{{< end-page >}}

{{< begin-page >}}

![Ms. Whiskers](imgs/feature.jpg)
{.feature-img-left}

{{% main-article-cont %}}



{{% quarter-article %}}
<!-- a quarter article should not be more than 600 char -->
## Art Corner
{{< author name="Yoshiko" >}}

![Ms. Whiskers](imgs/feature.jpg)
{.art-img}
{{% /quarter-article %}}

{{% quarter-article %}}
<!-- a quarter article should not be more than 600 char -->
## Art Corner
{{< author name="Matt" >}}

![Trump Buys Greenland](imgs/feature.jpg)
{.art-img}


{{< /quarter-article >}}

{{% quarter-article %}}
<!-- a quarter article should not be more than 600 char -->
## Puzzle

![Sudoku Puzzle](imgs/feature.jpg)
{.puzzle-img}
{{% /quarter-article %}}

{{< quarter-article markdownify >}}
<!-- a quarter article should not be more than 630 char -->
## Riddle #

Answer:

<button class="spoiler">INSERT_RIDDLE_ANSWER_HERE</button>
{{< /quarter-article >}}

{{% difficult-words %}}
<!-- max number of difficult words is 10 -->
## Difficult Words
* greet
* 挨拶する 

* useful
* 便利な；有用な  

* wild
* 荒っぽい；野生

* phrase
* フレーズ

* pretty  
* かなり




{{% /difficult-words %}}


{{< end-page >}}