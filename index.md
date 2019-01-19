---
title: |
  Créez vos documents avec ![R Markdown](https://raw.githubusercontent.com/rstudio/hex-stickers/master/PNG/rmarkdown.png){width=100 style="vertical-align: middle;"}
author: "Romain Lesur"
date: "21 janvier 2019"
output: 
  ioslides_presentation:
    widescreen: true
    self_contained: false
    logo: "assets/meetuprnantes.jpeg"
    keep_md: true
---



<style type="text/css">
.title-slide {
  background-image: url('assets/sharon-mccutcheon-576867-unsplash.jpg');
  background-size: cover;
  background-position: center;
  background-blend-mode: lighten;
}
</style>

## Pourquoi utiliser R Markdown ? {data-background=assets/2riz84.jpg data-background-position="50% 75%" data-background-size=70%}

## Pourquoi utiliser R Markdown ? {data-background=assets/2rfny8.jpg data-background-position="50% 75%" data-background-size=70%}

## Pourquoi utiliser R Markdown ? {data-background=assets/2rj0z1.jpg data-background-position="50% 75%" data-background-size=90%}

## Un principe : _Keep it simple_

<div class="columns-2">
<embed src="simple.pdf" type="application/pdf" width="100%" height="500px" />

<!--html_preserve--><div>
<iframe srcdoc="&lt;!DOCTYPE html&gt;&#10;&lt;html xmlns=&quot;http://www.w3.org/1999/xhtml&quot; lang=&quot;fr&quot; xml:lang=&quot;fr&quot;&gt;&#10;&lt;head&gt;&#10;  &lt;meta charset=&quot;utf-8&quot; /&gt;&#10;  &lt;meta name=&quot;generator&quot; content=&quot;pandoc&quot; /&gt;&#10;  &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0, user-scalable=yes&quot; /&gt;&#10;  &lt;title&gt;Fichier R Markdown&lt;/title&gt;&#10;  &lt;style type=&quot;text/css&quot;&gt;&#10;      code{white-space: pre-wrap;}&#10;      span.smallcaps{font-variant: small-caps;}&#10;      span.underline{text-decoration: underline;}&#10;      div.column{display: inline-block; vertical-align: top; width: 50%;}&#10;  &lt;/style&gt;&#10;  &lt;style type=&quot;text/css&quot;&gt;&#10;a.sourceLine { display: inline-block; line-height: 1.25; }&#10;a.sourceLine { pointer-events: none; color: inherit; text-decoration: inherit; }&#10;a.sourceLine:empty { height: 1.2em; position: absolute; }&#10;.sourceCode { overflow: visible; }&#10;code.sourceCode { white-space: pre; position: relative; }&#10;div.sourceCode { margin: 1em 0; }&#10;pre.sourceCode { margin: 0; }&#10;@media screen {&#10;div.sourceCode { overflow: auto; }&#10;}&#10;@media print {&#10;code.sourceCode { white-space: pre-wrap; }&#10;a.sourceLine { text-indent: -1em; padding-left: 1em; }&#10;}&#10;pre.numberSource a.sourceLine&#10;  { position: relative; }&#10;pre.numberSource a.sourceLine:empty&#10;  { position: absolute; }&#10;pre.numberSource a.sourceLine::before&#10;  { content: attr(data-line-number);&#10;    position: absolute; left: -5em; text-align: right; vertical-align: baseline;&#10;    border: none; pointer-events: all;&#10;    -webkit-touch-callout: none; -webkit-user-select: none;&#10;    -khtml-user-select: none; -moz-user-select: none;&#10;    -ms-user-select: none; user-select: none;&#10;    padding: 0 4px; width: 4em;&#10;    color: #aaaaaa;&#10;  }&#10;pre.numberSource { margin-left: 3em; border-left: 1px solid #aaaaaa;  padding-left: 4px; }&#10;div.sourceCode&#10;  {  }&#10;@media screen {&#10;a.sourceLine::before { text-decoration: underline; }&#10;}&#10;code span.al { color: #ff0000; font-weight: bold; } /* Alert */&#10;code span.an { color: #60a0b0; font-weight: bold; font-style: italic; } /* Annotation */&#10;code span.at { color: #7d9029; } /* Attribute */&#10;code span.bn { color: #40a070; } /* BaseN */&#10;code span.bu { } /* BuiltIn */&#10;code span.cf { color: #007020; font-weight: bold; } /* ControlFlow */&#10;code span.ch { color: #4070a0; } /* Char */&#10;code span.cn { color: #880000; } /* Constant */&#10;code span.co { color: #60a0b0; font-style: italic; } /* Comment */&#10;code span.cv { color: #60a0b0; font-weight: bold; font-style: italic; } /* CommentVar */&#10;code span.do { color: #ba2121; font-style: italic; } /* Documentation */&#10;code span.dt { color: #902000; } /* DataType */&#10;code span.dv { color: #40a070; } /* DecVal */&#10;code span.er { color: #ff0000; font-weight: bold; } /* Error */&#10;code span.ex { } /* Extension */&#10;code span.fl { color: #40a070; } /* Float */&#10;code span.fu { color: #06287e; } /* Function */&#10;code span.im { } /* Import */&#10;code span.in { color: #60a0b0; font-weight: bold; font-style: italic; } /* Information */&#10;code span.kw { color: #007020; font-weight: bold; } /* Keyword */&#10;code span.op { color: #666666; } /* Operator */&#10;code span.ot { color: #007020; } /* Other */&#10;code span.pp { color: #bc7a00; } /* Preprocessor */&#10;code span.sc { color: #4070a0; } /* SpecialChar */&#10;code span.ss { color: #bb6688; } /* SpecialString */&#10;code span.st { color: #4070a0; } /* String */&#10;code span.va { color: #19177c; } /* Variable */&#10;code span.vs { color: #4070a0; } /* VerbatimString */&#10;code span.wa { color: #60a0b0; font-weight: bold; font-style: italic; } /* Warning */&#10;  &lt;/style&gt;&#10;  &lt;!--[if lt IE 9]&gt;&#10;    &lt;script src=&quot;//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv-printshiv.min.js&quot;&gt;&lt;/script&gt;&#10;  &lt;![endif]--&gt;&#10;&lt;/head&gt;&#10;&lt;body&gt;&#10;&lt;header&gt;&#10;&lt;h1 class=&quot;title&quot;&gt;Fichier R Markdown&lt;/h1&gt;&#10;&lt;/header&gt;&#10;&lt;div class=&quot;sourceCode&quot; id=&quot;cb1&quot;&gt;&lt;pre class=&quot;sourceCode markdown&quot;&gt;&lt;code class=&quot;sourceCode markdown&quot;&gt;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-1&quot; data-line-number=&quot;1&quot;&gt;---&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-2&quot; data-line-number=&quot;2&quot;&gt;title: &amp;quot;Keep It Simple&amp;quot;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-3&quot; data-line-number=&quot;3&quot;&gt;author: &amp;quot;Romain Lesur&amp;quot;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-4&quot; data-line-number=&quot;4&quot;&gt;output: &lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-5&quot; data-line-number=&quot;5&quot;&gt;  pdf_document:&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-6&quot; data-line-number=&quot;6&quot;&gt;&lt;span class=&quot;bn&quot;&gt;    df_print: kable&lt;/span&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-7&quot; data-line-number=&quot;7&quot;&gt;---&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-8&quot; data-line-number=&quot;8&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-9&quot; data-line-number=&quot;9&quot;&gt;```{r setup, include=FALSE}&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-10&quot; data-line-number=&quot;10&quot;&gt;knitr::opts_chunk$set(echo = FALSE, message = FALSE)&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-11&quot; data-line-number=&quot;11&quot;&gt;```&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-12&quot; data-line-number=&quot;12&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-13&quot; data-line-number=&quot;13&quot;&gt;&lt;span class=&quot;fu&quot;&gt;## Introduction&lt;/span&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-14&quot; data-line-number=&quot;14&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-15&quot; data-line-number=&quot;15&quot;&gt;Quelques mots sur les données.&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-16&quot; data-line-number=&quot;16&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-17&quot; data-line-number=&quot;17&quot;&gt;&lt;span class=&quot;fu&quot;&gt;## Du texte et un graphique&lt;/span&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-18&quot; data-line-number=&quot;18&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-19&quot; data-line-number=&quot;19&quot;&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas euismod, dolor at faucibus finibus, lacus nunc gravida mauris, ac porttitor felis turpis a purus. Mauris aliquam risus ut erat accumsan, id gravida purus dignissim. Donec tortor est, fringilla sit amet magna at, mattis pulvinar erat. Aenean tellus ante, rutrum non purus eu, commodo vehicula leo. Mauris congue urna nec tristique eleifend. Sed tincidunt vel justo id pellentesque. Proin sagittis fermentum tellus, eu viverra neque eleifend at. Suspendisse potenti.&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-20&quot; data-line-number=&quot;20&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-21&quot; data-line-number=&quot;21&quot;&gt;Source du graphique : http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-22&quot; data-line-number=&quot;22&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-23&quot; data-line-number=&quot;23&quot;&gt;```{r graphique, fig.height=4}&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-24&quot; data-line-number=&quot;24&quot;&gt;library(ggplot2)&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-25&quot; data-line-number=&quot;25&quot;&gt;library(quantmod)&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-26&quot; data-line-number=&quot;26&quot;&gt;data(&amp;quot;economics&amp;quot;, package = &amp;quot;ggplot2&amp;quot;)&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-27&quot; data-line-number=&quot;27&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-28&quot; data-line-number=&quot;28&quot;&gt;&lt;span class=&quot;fu&quot;&gt;# Compute % Returns&lt;/span&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-29&quot; data-line-number=&quot;29&quot;&gt;economics$returns_perc &amp;lt;- c(0, diff(economics$psavert)/economics$psavert[-length(economics$psavert)])&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-30&quot; data-line-number=&quot;30&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-31&quot; data-line-number=&quot;31&quot;&gt;&lt;span class=&quot;fu&quot;&gt;# Create break points and labels for axis ticks&lt;/span&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-32&quot; data-line-number=&quot;32&quot;&gt;brks &amp;lt;- economics$date[seq(1, length(economics$date), 12)]&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-33&quot; data-line-number=&quot;33&quot;&gt;lbls &amp;lt;- lubridate::year(economics$date[seq(1, length(economics$date), 12)])&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-34&quot; data-line-number=&quot;34&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-35&quot; data-line-number=&quot;35&quot;&gt;&lt;span class=&quot;fu&quot;&gt;# Plot&lt;/span&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-36&quot; data-line-number=&quot;36&quot;&gt;ggplot(economics[1:100, ], aes(date, returns_perc)) + &lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-37&quot; data-line-number=&quot;37&quot;&gt;  geom_area() + &lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-38&quot; data-line-number=&quot;38&quot;&gt;  scale_x_date(breaks=brks, labels=lbls) + &lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-39&quot; data-line-number=&quot;39&quot;&gt;  theme(axis.text.x = element_text(angle=90)) + &lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-40&quot; data-line-number=&quot;40&quot;&gt;  labs(title=&amp;quot;Area Chart&amp;quot;, &lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-41&quot; data-line-number=&quot;41&quot;&gt;&lt;span class=&quot;bn&quot;&gt;       subtitle = &amp;quot;Perc Returns for Personal Savings&amp;quot;, &lt;/span&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-42&quot; data-line-number=&quot;42&quot;&gt;&lt;span class=&quot;bn&quot;&gt;       y=&amp;quot;% Returns for Personal savings&amp;quot;, &lt;/span&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-43&quot; data-line-number=&quot;43&quot;&gt;&lt;span class=&quot;bn&quot;&gt;       caption=&amp;quot;Source: economics&amp;quot;)&lt;/span&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-44&quot; data-line-number=&quot;44&quot;&gt;```&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-45&quot; data-line-number=&quot;45&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-46&quot; data-line-number=&quot;46&quot;&gt;&lt;span class=&quot;fu&quot;&gt;## Un tableau avec quelques données&lt;/span&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-47&quot; data-line-number=&quot;47&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-48&quot; data-line-number=&quot;48&quot;&gt;Voici un petit tableau :&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-49&quot; data-line-number=&quot;49&quot;&gt;&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-50&quot; data-line-number=&quot;50&quot;&gt;```{r tableau}&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-51&quot; data-line-number=&quot;51&quot;&gt;head(economics, n = 3L)&lt;/a&gt;&#10;&lt;a class=&quot;sourceLine&quot; id=&quot;cb1-52&quot; data-line-number=&quot;52&quot;&gt;```&lt;/a&gt;&lt;/code&gt;&lt;/pre&gt;&lt;/div&gt;&#10;&lt;/body&gt;&#10;&lt;/html&gt;" style="height:500px!important;"></iframe>
</div><!--/html_preserve-->

</div>

## R Markdown

This is an R Markdown presentation. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document.

## Slide with Bullets

- Bullet 1
- Bullet 2
- Bullet 3

## Différents languages autorisés


```r
names(knitr::knit_engines$get())
```

```
##  [1] "awk"       "bash"      "coffee"    "gawk"      "groovy"   
##  [6] "haskell"   "lein"      "mysql"     "node"      "octave"   
## [11] "perl"      "psql"      "Rscript"   "ruby"      "sas"      
## [16] "scala"     "sed"       "sh"        "stata"     "zsh"      
## [21] "highlight" "Rcpp"      "tikz"      "dot"       "c"        
## [26] "fortran"   "fortran95" "asy"       "cat"       "asis"     
## [31] "stan"      "block"     "block2"    "js"        "css"      
## [36] "sql"       "go"        "python"    "julia"
```

## Exemple : `python`



```python
a = 1 + 2
print(a)
```

```
## 3
```




```python
import pandas as pd
import numpy as np
dates = pd.date_range('20130101', periods=6)
df = pd.DataFrame(np.random.randn(6,4), index=dates, columns=list('ABCD'))
print(df)
```

```
##                    A         B         C         D
## 2013-01-01 -0.609552  0.655283 -0.223467  0.021406
## 2013-01-02  0.487587 -0.792637  0.810214 -0.465211
## 2013-01-03 -0.817697 -1.368888  0.548597  0.271364
## 2013-01-04  0.553751 -1.208820  0.553546  1.309373
## 2013-01-05 -1.335506  1.040081 -1.164823  0.860691
## 2013-01-06  1.786913 -0.467727  0.546121  0.066572
```


## Exemple : `node.js`


```javascript
const hi = (name) => {
  console.log("Hello " + name + "!");
}

hi("Bob");
```

```
## Hello Bob!
```

## Exemple : `SQL`


```r
con <- DBI::dbConnect(RSQLite::SQLite(), path = ":memory:")
DBI::dbWriteTable(con, "mtcars", mtcars)
```


```sql
SELECT name FROM sqlite_master WHERE type='table';
```


<div class="knitsql-table">


Table: 1 records

|name   |
|:------|
|mtcars |

</div>

---


```sql
SELECT mpg, cyl, disp FROM mtcars
       LIMIT 3;
```


<div class="knitsql-table">


Table: 3 records

  mpg   cyl   disp
-----  ----  -----
 21.0     6    160
 21.0     6    160
 22.8     4    108

</div>

**Se déconnecter :**


```r
DBI::dbDisconnect(con)
```


## Hacker R Markdown

### Hacker le bouton `knit` de RStudio

Rajouter dans l'en-tête YAML du fichier `Rmd` une ligne qui renvoie une fonction $\lambda$ ayant pour arguments `(inputFile, encoding)`

```yaml
knit: (function(inputFile, encoding){...})
```

Si en plus la fonction comprend `message("Output created: ", outputFile)`, le viewer de RStudio l'ouvrira.

Voir <https://github.com/rstudio/rmarkdown/issues/277>

- Hacker `knitr`
