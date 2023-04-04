
<!-- README.md is generated from README.Rmd. Please edit that file -->

# About the Paper

The following Readme provides additional information and files for the
Paper:

***“The Standardization of Accounting Language”.***

# Concept List

The full concept list can be downloaded
<a href="2_output/concept_list.xlsx" download="2_output/concept_list.xlsx">here</a>.

The concept list includes the following columns:

<table>
<colgroup>
<col style="width: 15%" />
<col style="width: 84%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">Column</th>
<th style="text-align: left;">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><code>cid</code></td>
<td style="text-align: left;">The Concept Identifier</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>tid</code></td>
<td style="text-align: left;">The Term Identifier</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>term</code></td>
<td style="text-align: left;">The standardized Term</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>cat1</code></td>
<td style="text-align: left;"><p><strong>Category 1:</strong> Indicator
column to what class a concept belongs</p>
<ul>
<li><p><strong>FinA</strong>: Financial Accounting Concept</p></li>
<li><p><strong>ManA</strong>: Managerial Accounting Concepts</p></li>
<li><p><strong>BusA</strong>: Business Concepts</p></li>
</ul></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong><code>cat2</code></strong></td>
<td style="text-align: left;"><p><strong>Category 2:</strong> Indicator
column to what class a concept belongs</p>
<ul>
<li><strong>GAAP:</strong> Either an IFRS or US GAAP Concept</li>
</ul></td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>cat3</code></td>
<td style="text-align: left;"><p><strong>Category 3:</strong> Indicator
column to what class a concept belongs</p>
<ul>
<li><p><strong>IS</strong>: Income Statement Concepts</p></li>
<li><p><strong>BS:</strong> Balance Sheet Concepts</p></li>
<li><p><strong>CF:</strong> Cash Flow Statement Concepts</p></li>
</ul></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>avg_ngram</code></td>
<td style="text-align: left;">The average N-Gram of all the terms within
the concept (i.e. of how many words a term is composed)</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>avg_sim</code></td>
<td style="text-align: left;">Average textual similarity of the terms
within the concept</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>size</code></td>
<td style="text-align: left;">The size of the concept (i.e. how many
terms are grouped within a concept)</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>complex_score</code></td>
<td style="text-align: left;">Linear combination of size, avg_ngram and
avg_sim (Scaled between 0-1)</td>
</tr>
</tbody>
</table>

The tables below show two example concepts for our concept list.

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

The full term list can be downloaded
<a href="2_output/term_list.xlsx" download="2_output/term_list.xlsx">here</a>.

The concept list includes the following columns:

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">Column</th>
<th style="text-align: left;">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><code>cid</code></td>
<td style="text-align: left;">The Concept Identifier</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>tid</code></td>
<td style="text-align: left;">The Term Identifier</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>term</code></td>
<td style="text-align: left;">The standardized Term</td>
</tr>
<tr class="even">
<td style="text-align: left;"><code>term_raw</code></td>
<td style="text-align: left;">The raw Term</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>cat1</code></td>
<td style="text-align: left;"><p><strong>Category 1:</strong> Indicator
column to what class a concept belongs</p>
<ul>
<li><p><strong>FinA</strong>: Financial Accounting Concept</p></li>
<li><p><strong>ManA</strong>: Managerial Accounting Concepts</p></li>
<li><p><strong>BusA</strong>: Business Concepts</p></li>
</ul></td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong><code>cat2</code></strong></td>
<td style="text-align: left;"><p><strong>Category 2:</strong> Indicator
column to what class a concept belongs</p>
<ul>
<li><strong>GAAP:</strong> Either an IFRS or US GAAP Concept</li>
</ul></td>
</tr>
<tr class="odd">
<td style="text-align: left;"><code>cat3</code></td>
<td style="text-align: left;"><p><strong>Category 3:</strong> Indicator
column to what class a concept belongs</p>
<ul>
<li><p><strong>IS</strong>: Income Statement Concepts</p></li>
<li><p><strong>BS:</strong> Balance Sheet Concepts</p></li>
<li><p><strong>CF:</strong> Cash Flow Statement Concepts</p></li>
</ul></td>
</tr>
</tbody>
</table>

The table below shows the first ten terms of our term list:

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
100
</td>
<td style="text-align:left;">
accident year
</td>
<td style="text-align:left;">
accident year
</td>
<td style="text-align:left;">
BusA
</td>
<td style="text-align:left;">
GAAP
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
101
</td>
<td style="text-align:left;">
accidental damage
</td>
<td style="text-align:left;">
accidental damage
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
102
</td>
<td style="text-align:left;">
accommodation bill
</td>
<td style="text-align:left;">
accommodation bill
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
103
</td>
<td style="text-align:left;">
accommodation endorsement
</td>
<td style="text-align:left;">
accomodation endorsement
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
104
</td>
<td style="text-align:left;">
accommodation party
</td>
<td style="text-align:left;">
accommodation party
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
105
</td>
<td style="text-align:left;">
accord and satisfaction
</td>
<td style="text-align:left;">
accord and satisfaction
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
106
</td>
<td style="text-align:left;">
accord to the technical principle of life assurance
</td>
<td style="text-align:left;">
according to the technical principles of life assurance
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
107
</td>
<td style="text-align:left;">
account
</td>
<td style="text-align:left;">
account\|accounts
</td>
<td style="text-align:left;">
FinA
</td>
<td style="text-align:left;">
GAAP
</td>
<td style="text-align:left;">
BS
</td>
</tr>
<tr>
<td style="text-align:right;">
108
</td>
<td style="text-align:left;">
account administration charge
</td>
<td style="text-align:left;">
account administration charges
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
109
</td>
<td style="text-align:left;">
account aging
</td>
<td style="text-align:left;">
account aging
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

In order to clean our term and concept list we use several additional
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

Below we show the first ten entries of this list:

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

Below we show the first ten entries of this list:

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

Below we show the first ten entries of this list:

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

## Lemmatization List

<div style="text-align: justify">

We lemmatize our terms to account for different inflectional endings and
plurals (e.g., “assets” and “asset”) and remove all punctuation

</div>

The full list can be downloaded
<a href="2_output/lemma_list.xlsx" download="2_output/lemma_list.xlsx">here</a>.

Below we show the first ten entries of this list:

<table class=" lightable-paper table" style="font-family: &quot;Arial Narrow&quot;, arial, helvetica, sans-serif; margin-left: auto; margin-right: auto; font-size: 10px; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="text-align:left;">
token
</th>
<th style="text-align:left;">
lemma
</th>
<th style="text-align:right;">
relemma
</th>
<th style="text-align:left;">
lemma_new
</th>
<th style="text-align:left;">
compund
</th>
<th style="text-align:right;">
non_english
</th>
<th style="text-align:right;">
acronym_abbreviation
</th>
<th style="text-align:right;">
location_language
</th>
<th style="text-align:right;">
monetary_unit
</th>
<th style="text-align:right;">
proper_noun
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
aborted
</td>
<td style="text-align:left;">
abort
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
about
</td>
<td style="text-align:left;">
about
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
above
</td>
<td style="text-align:left;">
above
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
abridged
</td>
<td style="text-align:left;">
abridge
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
abroad
</td>
<td style="text-align:left;">
abroad
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
abs
</td>
<td style="text-align:left;">
ab
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:left;">
abs
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
absence
</td>
<td style="text-align:left;">
absence
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
absences
</td>
<td style="text-align:left;">
absence
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
absolute
</td>
<td style="text-align:left;">
absolute
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
absolutism
</td>
<td style="text-align:left;">
absolutism
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
</tbody>
</table>
