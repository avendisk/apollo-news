+++
title = "{{ replace .Name "-" " " | title }}"
date = {{ .Date }}
draft = true
featured_image = "imgs/feature.png"
featured_image_caption = "feature caption"

[params]
    paper_title = "Apollo News"
    actual_date = {{ .Date }}
    issue_num = 1
+++

<!-- you can put percent signs on this instead of <> to process markdown -->
{{< begin-page >}}
{{< paper-heading >}}



<!-- The main english article should not be more than 740 characters -->
<!-- The main japanese article should not be more than 350 characters -->
{{< main-article >}}
<h2> INSERT_ARTICLE_TITLE_HERE </h2>
{{< author name="INSERT_AUTHOR_NAME_HERE" >}}

{{< /main-article >}}

![ALT_TEXT_HERE](imgs/feature.jpg)
{.feature-img}

{{< articles/custom-article >}}
<!-- a quarter article should not be more than 600 char -->
<h2>Review: REVIEW_TITLE</h2>
{{< author name="INSERT_AUTHOR_NAME_HERE" >}}

<!-- Change the Ramen rating number to be the number out of five -->
{{< articles/ramen-ratings 3 >}}

{{< /articles/custom-article >}}



{{% articles/custom-article %}}
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
{{% /articles/custom-article %}}


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

<!-- -------------------------------------------------------- -->
<!-- ---------------- BEGINNING OF PAGE 2-------------------- -->
<!-- -------------------------------------------------------- -->
{{< begin-page >}}

![Ms. Whiskers](imgs/feature.jpg)
{.feature-img-left}

{{% main-article-cont %}}



{{% articles/custom-article %}}
<!-- a quarter article should not be more than 600 char -->
## Art Corner
{{< author name="Yoshiko" >}}

![Ms. Whiskers](imgs/feature.jpg)
{.art-img}
{{% /articles/custom-article %}}

{{% articles/custom-article %}}
<!-- a quarter article should not be more than 600 char -->
## Art Corner
{{< author name="Matt" >}}

![Trump Buys Greenland](imgs/feature.jpg)
{.art-img}

{{% /articles/custom-article %}}


{{% articles/custom-article %}}
<!-- a quarter article should not be more than 600 char -->
## Puzzle

![Sudoku Puzzle](imgs/feature.jpg)
{.puzzle-img}
{{% /articles/custom-article %}}

{{% articles/custom-article %}}
<!-- a quarter article should not be more than 630 char -->
## Riddle #
<br><br><br>
Answer:

<button class="spoiler">INSERT_RIDDLE_ANSWER_HERE</button>
{{% /articles/custom-article %}}

{{% difficult-words %}}
<!-- max number of difficult words is 10 -->
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