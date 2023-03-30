
<!-- README.md is generated from README.Rmd. Please edit that file -->

# About the Paper

The following Readme provides additional information and files for the
Paper:

***“The Standardization of Accounting Language”.***

# Concept List

The tables below show two example concepts for the paper: ***“The
Standardization of Accounting Language”.***

The full concept list can be downloaded
<a href="2_output/concept_list.xlsx" download="2_output/concept_list.xlsx">here</a>.

The concept list includes the following columns:

| Column          | Description                                                                                                                                                     |
|:----------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `cid`           | The Concept Identifier                                                                                                                                          |
| `tid`           | The Term Identifier                                                                                                                                             |
| `term`          | The standardized Term                                                                                                                                           |
| `cat1`          | **Category 1:** which includes **“FinA”** for Financial Accounting Concepts, **“ManA”** for Managerial Accounting Concepts and **“BusA”** for Business Concepts |
| **`cat2`**      | **Category 2:** Indicator column if the concept is a **GAAP** concept                                                                                           |
| `cat3`          | **Category 3:** which includes **“IS”** for Income Statement Concepts, **“BS”** for Balance Sheet Concepts and **“CF”** for Cash Flow Statement Concepts        |
| `avg_ngram`     | The average N-Gram of all the terms within the concept (i.e. of how many words a term is composed)                                                              |
| `avg_sim`       | Average textual similarity of the terms within the concept                                                                                                      |
| `size`          | The size of the concept (i.e. how many terms are grouped within a concept)                                                                                      |
| `complex_score` | Linear combination of size, avg_ngram and avg_sim (Scaled between 0-1)                                                                                          |

## Concept 1: ABC Costing

<table class=" lightable-paper table" style="font-family: &quot;Arial Narrow&quot;, arial, helvetica, sans-serif; margin-left: auto; margin-right: auto; font-size: 10px; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="text-align:right;">
cid
</th>
<th style="text-align:right;">
tid
</th>
<th style="text-align:left;">
term
</th>
<th style="text-align:left;">
cat1
</th>
<th style="text-align:left;">
cat2
</th>
<th style="text-align:left;">
cat3
</th>
<th style="text-align:right;">
size
</th>
<th style="text-align:right;">
avg_ngram
</th>
<th style="text-align:right;">
avg_sim
</th>
<th style="text-align:right;">
complex_score
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
37
</td>
<td style="text-align:left;">
abc costing
</td>
<td style="text-align:left;">
ManA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
5
</td>
<td style="text-align:right;">
2.4
</td>
<td style="text-align:right;">
0.7643706
</td>
<td style="text-align:right;">
0.7342886
</td>
</tr>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
38
</td>
<td style="text-align:left;">
abc costing method
</td>
<td style="text-align:left;">
ManA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
5
</td>
<td style="text-align:right;">
2.4
</td>
<td style="text-align:right;">
0.7643706
</td>
<td style="text-align:right;">
0.7342886
</td>
</tr>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
40
</td>
<td style="text-align:left;">
abc method
</td>
<td style="text-align:left;">
ManA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
5
</td>
<td style="text-align:right;">
2.4
</td>
<td style="text-align:right;">
0.7643706
</td>
<td style="text-align:right;">
0.7342886
</td>
</tr>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
920
</td>
<td style="text-align:left;">
activity based costing
</td>
<td style="text-align:left;">
ManA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
5
</td>
<td style="text-align:right;">
2.4
</td>
<td style="text-align:right;">
0.7643706
</td>
<td style="text-align:right;">
0.7342886
</td>
</tr>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
926
</td>
<td style="text-align:left;">
activity costing
</td>
<td style="text-align:left;">
ManA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
5
</td>
<td style="text-align:right;">
2.4
</td>
<td style="text-align:right;">
0.7643706
</td>
<td style="text-align:right;">
0.7342886
</td>
</tr>
</tbody>
</table>

## Concept 2: Accounts Payable

<table class=" lightable-paper table" style="font-family: &quot;Arial Narrow&quot;, arial, helvetica, sans-serif; margin-left: auto; margin-right: auto; font-size: 10px; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="text-align:right;">
cid
</th>
<th style="text-align:right;">
tid
</th>
<th style="text-align:left;">
term
</th>
<th style="text-align:left;">
cat1
</th>
<th style="text-align:left;">
cat2
</th>
<th style="text-align:left;">
cat3
</th>
<th style="text-align:right;">
size
</th>
<th style="text-align:right;">
avg_ngram
</th>
<th style="text-align:right;">
avg_sim
</th>
<th style="text-align:right;">
complex_score
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:right;">
2
</td>
<td style="text-align:right;">
158
</td>
<td style="text-align:left;">
account payable
</td>
<td style="text-align:left;">
FinA
</td>
<td style="text-align:left;">
GAAP
</td>
<td style="text-align:left;">
CF
</td>
<td style="text-align:right;">
4
</td>
<td style="text-align:right;">
2.25
</td>
<td style="text-align:right;">
0.7282598
</td>
<td style="text-align:right;">
0.676223
</td>
</tr>
<tr>
<td style="text-align:right;">
2
</td>
<td style="text-align:right;">
48456
</td>
<td style="text-align:left;">
trade account payable
</td>
<td style="text-align:left;">
FinA
</td>
<td style="text-align:left;">
GAAP
</td>
<td style="text-align:left;">
CF
</td>
<td style="text-align:right;">
4
</td>
<td style="text-align:right;">
2.25
</td>
<td style="text-align:right;">
0.7282598
</td>
<td style="text-align:right;">
0.676223
</td>
</tr>
<tr>
<td style="text-align:right;">
2
</td>
<td style="text-align:right;">
48507
</td>
<td style="text-align:left;">
trade creditor
</td>
<td style="text-align:left;">
FinA
</td>
<td style="text-align:left;">
GAAP
</td>
<td style="text-align:left;">
CF
</td>
<td style="text-align:right;">
4
</td>
<td style="text-align:right;">
2.25
</td>
<td style="text-align:right;">
0.7282598
</td>
<td style="text-align:right;">
0.676223
</td>
</tr>
<tr>
<td style="text-align:right;">
2
</td>
<td style="text-align:right;">
48559
</td>
<td style="text-align:left;">
trade payable
</td>
<td style="text-align:left;">
FinA
</td>
<td style="text-align:left;">
GAAP
</td>
<td style="text-align:left;">
CF
</td>
<td style="text-align:right;">
4
</td>
<td style="text-align:right;">
2.25
</td>
<td style="text-align:right;">
0.7282598
</td>
<td style="text-align:right;">
0.676223
</td>
</tr>
</tbody>
</table>

# Term List

The table below shows the first ten terms for the paper: ***“The
Standardization of Accounting Language”.***

The full concept list can be downloaded
<a href="2_output/term_list.xlsx" download="2_output/term_list.xlsx">here</a>.

The concept list includes the following columns:

| Column     | Description                                                                                                                                                     |
|:-----------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `cid`      | The Concept Identifier                                                                                                                                          |
| `tid`      | The Term Identifier                                                                                                                                             |
| `term`     | The standardized Term                                                                                                                                           |
| `term_raw` | The raw Term                                                                                                                                                    |
| `cat1`     | **Category 1:** which includes **“FinA”** for Financial Accounting Concepts, **“ManA”** for Managerial Accounting Concepts and **“BusA”** for Business Concepts |
| **`cat2`** | **Category 2:** Indicator column if the concept is a **GAAP** concept                                                                                           |
| `cat3`     | **Category 3:** which includes **“IS”** for Income Statement Concepts, **“BS”** for Balance Sheet Concepts and **“CF”** for Cash Flow Statement Concepts        |

<table class=" lightable-paper table" style="font-family: &quot;Arial Narrow&quot;, arial, helvetica, sans-serif; margin-left: auto; margin-right: auto; font-size: 10px; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="text-align:right;">
tid
</th>
<th style="text-align:left;">
term
</th>
<th style="text-align:left;">
term_raw
</th>
<th style="text-align:left;">
cat1
</th>
<th style="text-align:left;">
cat2
</th>
<th style="text-align:left;">
cat3
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:left;">
10 k
</td>
<td style="text-align:left;">
10 - k
</td>
<td style="text-align:left;">
FinA
</td>
<td style="text-align:left;">
GAAP
</td>
<td style="text-align:left;">
CF
</td>
</tr>
<tr>
<td style="text-align:right;">
2
</td>
<td style="text-align:left;">
10 ksb
</td>
<td style="text-align:left;">
10 - ksb
</td>
<td style="text-align:left;">
BusA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
3
</td>
<td style="text-align:left;">
10 q
</td>
<td style="text-align:left;">
10 - q
</td>
<td style="text-align:left;">
FinA
</td>
<td style="text-align:left;">
GAAP
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
4
</td>
<td style="text-align:left;">
12 month expect credit loss
</td>
<td style="text-align:left;">
12 - month expected credit losses
</td>
<td style="text-align:left;">
FinA
</td>
<td style="text-align:left;">
GAAP
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
5
</td>
<td style="text-align:left;">
13 th period
</td>
<td style="text-align:left;">
13 th period
</td>
<td style="text-align:left;">
BusA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
6
</td>
<td style="text-align:left;">
15 minute rule
</td>
<td style="text-align:left;">
15 minute rule
</td>
<td style="text-align:left;">
BusA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
7
</td>
<td style="text-align:left;">
18 25 trust
</td>
<td style="text-align:left;">
18 - 25 trust
</td>
<td style="text-align:left;">
BusA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
8
</td>
<td style="text-align:left;">
2 way match
</td>
<td style="text-align:left;">
2 - way matching
</td>
<td style="text-align:left;">
BusA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
9
</td>
<td style="text-align:left;">
3 rule
</td>
<td style="text-align:left;">
3% rule
</td>
<td style="text-align:left;">
FinA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
10
</td>
<td style="text-align:left;">
3 way match
</td>
<td style="text-align:left;">
3 - way matching
</td>
<td style="text-align:left;">
BusA
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
</tbody>
</table>

# Additional Input Lists

<div style="text-align: justify">

In order to clean out term and concept list we use several additional
input list, the complete pipeline can be seen in the Online Appendix to
the paper (section 1).

</div>

## British English vs. American English

<div style="text-align: justify">

We normalize different varieties of English (i.e., “capitalization” and
“capitalisation”) by converting all British-English spelling varieties
of a word to American-English, we do so by relying on an
American/British English Dictionary that contains more than 1,700
different word combinations.

</div>

<http://www.tysto.com/uk-us-spelling-list.html>

The full list can be downloaded
<a href="2_output/us_uk.xlsx" download="2_output/us_uk.xlsx">here</a>.

<table class=" lightable-paper table" style="font-family: &quot;Arial Narrow&quot;, arial, helvetica, sans-serif; margin-left: auto; margin-right: auto; font-size: 10px; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="text-align:left;">
uk
</th>
<th style="text-align:left;">
us
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
accessorise
</td>
<td style="text-align:left;">
accessorize
</td>
</tr>
<tr>
<td style="text-align:left;">
accessorised
</td>
<td style="text-align:left;">
accessorized
</td>
</tr>
<tr>
<td style="text-align:left;">
accessorises
</td>
<td style="text-align:left;">
accessorizes
</td>
</tr>
<tr>
<td style="text-align:left;">
accessorising
</td>
<td style="text-align:left;">
accessorizing
</td>
</tr>
<tr>
<td style="text-align:left;">
acclimatisation
</td>
<td style="text-align:left;">
acclimatization
</td>
</tr>
<tr>
<td style="text-align:left;">
acclimatise
</td>
<td style="text-align:left;">
acclimatize
</td>
</tr>
<tr>
<td style="text-align:left;">
acclimatised
</td>
<td style="text-align:left;">
acclimatized
</td>
</tr>
<tr>
<td style="text-align:left;">
acclimatises
</td>
<td style="text-align:left;">
acclimatizes
</td>
</tr>
<tr>
<td style="text-align:left;">
acclimatising
</td>
<td style="text-align:left;">
acclimatizing
</td>
</tr>
<tr>
<td style="text-align:left;">
accoutrements
</td>
<td style="text-align:left;">
accouterments
</td>
</tr>
</tbody>
</table>

## Stylistic Differences due to hyphenations

<div style="text-align: justify">

We account for stylistic differences arising from different hyphenations
and the inclusion/exclusion of blank characters (i.e., “non-current
assets”, “non current assets” and “noncurrent assets”). For this
purpose, we build a custom dictionary with more than 300 different split
term pairs, and we always convert a word within a term to a split,
hyphen-free version (i.e. the word “noncurrent” is converted to “non
current”).

</div>

The full list can be downloaded
<a href="2_output/split_terms.xlsx" download="2_output/split_terms.xlsx">here</a>.

<table class=" lightable-paper table" style="font-family: &quot;Arial Narrow&quot;, arial, helvetica, sans-serif; margin-left: auto; margin-right: auto; font-size: 10px; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="text-align:left;">
unsplit
</th>
<th style="text-align:left;">
split
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
nonaccretable
</td>
<td style="text-align:left;">
non accretable
</td>
</tr>
<tr>
<td style="text-align:left;">
nonaccrual
</td>
<td style="text-align:left;">
non accrual
</td>
</tr>
<tr>
<td style="text-align:left;">
nonallowable
</td>
<td style="text-align:left;">
non allowable
</td>
</tr>
<tr>
<td style="text-align:left;">
nonamortisable
</td>
<td style="text-align:left;">
non amortisable
</td>
</tr>
<tr>
<td style="text-align:left;">
nonamortizable
</td>
<td style="text-align:left;">
non amortizable
</td>
</tr>
<tr>
<td style="text-align:left;">
noncallable
</td>
<td style="text-align:left;">
non callable
</td>
</tr>
<tr>
<td style="text-align:left;">
noncancelable
</td>
<td style="text-align:left;">
non cancelable
</td>
</tr>
<tr>
<td style="text-align:left;">
noncash
</td>
<td style="text-align:left;">
non cash
</td>
</tr>
<tr>
<td style="text-align:left;">
noncatastrophic
</td>
<td style="text-align:left;">
non catastrophic
</td>
</tr>
<tr>
<td style="text-align:left;">
noncompete
</td>
<td style="text-align:left;">
non compete
</td>
</tr>
</tbody>
</table>

## Stop words

<div style="text-align: justify">

We remove terms that equal a stop word (e.g., “and”, “or”, …) by
complementing Loughran and McDonald’s stop word lists with more than 550
custom stop words and phrases (proper names, currencies, stock
exchanges, non English terms and geographic regions) we identified from
our raw sources.

</div>

The full list can be downloaded
<a href="2_output/stopwords.xlsx" download="2_output/stopwords.xlsx">here</a>.

<table class=" lightable-paper table" style="font-family: &quot;Arial Narrow&quot;, arial, helvetica, sans-serif; margin-left: auto; margin-right: auto; font-size: 10px; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="text-align:left;">
stop
</th>
<th style="text-align:left;">
stop_type
</th>
<th style="text-align:left;">
origin
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
pwc
</td>
<td style="text-align:left;">
auditor
</td>
<td style="text-align:left;">
own
</td>
</tr>
<tr>
<td style="text-align:left;">
kpmg
</td>
<td style="text-align:left;">
auditor
</td>
<td style="text-align:left;">
own
</td>
</tr>
<tr>
<td style="text-align:left;">
pricewaterhousecoopers
</td>
<td style="text-align:left;">
auditor
</td>
<td style="text-align:left;">
own
</td>
</tr>
<tr>
<td style="text-align:left;">
deloitte
</td>
<td style="text-align:left;">
auditor
</td>
<td style="text-align:left;">
own
</td>
</tr>
<tr>
<td style="text-align:left;">
deloitte touche
</td>
<td style="text-align:left;">
auditor
</td>
<td style="text-align:left;">
own
</td>
</tr>
<tr>
<td style="text-align:left;">
ey
</td>
<td style="text-align:left;">
auditor
</td>
<td style="text-align:left;">
own
</td>
</tr>
<tr>
<td style="text-align:left;">
ernst and young
</td>
<td style="text-align:left;">
auditor
</td>
<td style="text-align:left;">
own
</td>
</tr>
<tr>
<td style="text-align:left;">
adopeng
</td>
<td style="text-align:left;">
currency
</td>
<td style="text-align:left;">
own
</td>
</tr>
<tr>
<td style="text-align:left;">
afghani
</td>
<td style="text-align:left;">
currency
</td>
<td style="text-align:left;">
L&M
</td>
</tr>
<tr>
<td style="text-align:left;">
ariary
</td>
<td style="text-align:left;">
currency
</td>
<td style="text-align:left;">
L&M
</td>
</tr>
</tbody>
</table>

## General Language Terms

<div style="text-align: justify">

We exclude accounting terms which also have a (different) meaning in
*general* language (e.g., “entry”) and which we identify with the
*2of12inf* dictionary which is a word list that includes more than
80,000 words (See Loughran and McDonald, 2011, 2016).

</div>

<http://wordlist.aspell.net/12dicts-readme-r4/>.

# Additional Packages

There are two packages that come with the paper and are free to use.

## Package 1: Search for Multiword Expressions in a Corpus

This is the package we use for retrieving the position of our terms in
our annual report corpus.

The package can be wound here:
<https://github.com/MatthiasUckert/rTermCount>

## Package 2: Multidimensional Name Matching

This is the package we use for matching our annual report data set to
Worldscope

The package can be wound here:
<https://github.com/MatthiasUckert/rMatching>
