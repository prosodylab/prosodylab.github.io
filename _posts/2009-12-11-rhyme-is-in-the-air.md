---
layout: post
title: rhyme is in the air
date: 2009-12-11 13:03:32.000000000 -05:00
type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- discussion
- prosodylab
tags: []
meta:
  _edit_last: '2'
author:
  login: chael
  email: chael.wagner@gmail.com
  display_name: chael
  first_name: Michael
  last_name: Wagner
permalink: "/2009/rhyme-is-in-the-air/"
---
_[see also a more recent post [here](http://prosodylab.org/?p=459). mw, august 8 2010_]

[Kate McCurdy](http://www.wjh.harvard.edu/~lds/index.html?snedekerlab.html) and I are currently working on cross-linguistic differences in constraints on rhyme. Here's a draft of a recent [paper](http://prosodylab.org/~chael/www/wagnermccurdy09_draft.pdf) that proposes an explanation for why 'identity' rhyme is considered a satisfactory rhyme in French but not in English. We relate this difference to the way information structure affects prosody in those languages, drawing on an observation by Edwin Williams that suggests that focus- and givenness marking in English has been 'overgeneralized' to phonological identity in such a way that sentences can sound infelicitous just because they end with phonological identical material.

A rhyme is usually defined as a pair of words that are identical from the last accented vowel to the end of the word or line (wear/bear). Identity rhyme (or: rime très riche) is a rhyme pair in which the phonological material from the accented syllable including the onset until the end of the word or line are identical (to bear/a bear). A special case are homophones, in which the entire last words containing the last accented vowel of the line are identical. In our study we focus on rhymes that are phonologically identical but differ in meaning, because rhymes that are identical in phonology and meaning might be bad because they're repetitious. Identity rhyme is different from mere 'rime riche,' in which an additional consonant is shared, but the rhymes are not fully identical (train, crane). While identity rhymes are considered poor and are rare in languages such as English or German, rime riche is quite well attested. In some other languages, French is one example, identity rhymes are ubiquitous. Of course, it could well be that this is an accidental differences stemming from the different poetic traditions in these languages, but our working hypothesis is that there is more to this.

A simple illustration of the cross-linguistic differences: One way we try to compare usage of rhyme across languages is to look translations of rhymed poetry. We have been collecting translations of the illustrated children's book 'Max & Moritz' by Wilhelm Busch (first published in German in 1865).

![max & Moritz]({{ site.baseurl }}/assets/images/2009/12/maxmoritz.jpg)

We find quite a difference in the frequency of occurrence of different rhyme types. The translations we have numbers for so far are from about 30 years ago Obviously, the actual numbers don't mean much, and we'll have to see whether the overall difference is consistent across the various translations into the two languages. Also, there could be differences depending on genre. Max & Moritz is rather colloquial, which we thought was an advantage, since translators might feel less obliged to follow what is considered prestige-rhyming in the target language. However, in our experience so far it seems to be quite clear that the languages differ dramatically with respect to identity rhyme (but apparently not with respect to rime riche):

| | # Rhymes | # Rimes Riches | # Identity Rhymes | # Homophones / %homophones among id rhymes |
| German | 208 | 7 (3.4%) | 0 | 0 |
| English I | 208 | 6 (2.9%) | 1 (0.5%) | 0 |
| English II | 198 | 11 (5.5%) | 0 | 0 |
| English III | 211 | 4 (1.9%) | 0 | 0 |
| French I | 208 | 6 (2.9%) | 76 (36.5%) | 2 (2.7 %) |
| French II | 209 | 4 (1.9%) | 63 (30.1%) | 3 (4.8 %) |
| French III | 174 | 3 (1.4%) | 30 (17.0%) | 4 (13.3 %) |

Our hypothesis is that French differs from English because of differences in how **information structure** affects prosody (see our paper). But we're currently doing some follow-up work looking at how **differences in lexical statistics affects the usage of rhyme**.

Coincidentally, two days ago Mark Liberman at the [Language Log](http://languagelog.ldc.upenn.edu/nll/) published a [post](http://languagelog.ldc.upenn.edu/nll/?p=1946) on just that topic (thanks to Bob Ladd for pointing out the post to me). He notes that no one seems to have taken a close look at the lexical statistics involved in rhyming. For example, if you partition the lexicon of English into rhyme cohorts, how many cohorts does it break into, and how many words are on average in a cohort?

We've been looking at just these questions, on the hypothesis that the size of the rhyme cohorts (both the actual size of individual cohorts within a language and the average/median size across cohorts) might explain some of the differences between languages--a factor we didn't control in our experiments so far. Maybe constraints on rhyme reflect the distribution of the rhyming 'resources' in the lexicon. Could the constraint against identity rhyme be explained in this way, rather than invoking our focus-related explanation?

There is some evidence from priming studies that rhyme plays a role in the activation of words in lexical processing (see [Allopenna et al., JML 38, 1998](http://www.bcs.rochester.edu/people/mtan/publications/1998Allopenna_JML.pdf), and references therein), so it seems quite plausible that lexical statistics could influence our intuitions on rhyme.

Here are some of the numbers that we found (these are likely to change once we take into account some of the issues Mark raises in his post). For our English stats we used the same corpus that Mark used, [Celex](http://www.ldc.upenn.edu/Catalog/CatalogEntry.jsp?catalogId=LDC96L14), the French stats were computed based on [Lexique](http://www.lexique.org/english/):

| | English | French |
| #Words | 160595 | 142693 |
| # Rhyme Cohorts | 40903 | 624 |
| # Median Length | 1 | 9 |
| # Average Length | 3.9 | 280.7 |
| # Identity Rhyme Cohorts | 62681 | 4077 |
| # Median Length | 1 | 4 |
| # Average Length | 2.6 | 32.7 |
| % Homophones among Identity Rhymes | 0.01% | 0.03% |

It's clear that the languages differ dramatically in their rhyming cohorts. This is not unexpected given the phonological differences (in French the last syllable is the accented) and morphological differences (many words in French rhyme because they're suffixed with the same derivational or inflectional affix, they're 'homoeoteleuton' ). There are various things that one could improve in those counts, for example we didn't consider at all difference and similarity in meaning, which is bound to be relevant, or now many of these rhymes are identical because they are morphologically related, but controlling for these factors is unlikely to blur the overall distinction between the languages.

However, it's not clear how one would expect these differences in lexical statistics to play out in what kinds of rhymes are deemed satisfactory. For example, one might think that rhyming is all-too-easy in French, and this is why additional constraints are needed, such as identity of the onset, to make the game more interesting. This is the 'the rarer the better' theory of what rhymes count as good. But then non-identity rhymes should be less satisfactory than identity rhymes because they're easier to come up with, but we didn't find that in our data. Also, if rarer rhymes are better, why is it that identity rhymes in English aren't better than non-identity rhymes, rather than worse?

Another possibility is that only those rhymes are deemed good that occur with sufficient frequency outside of poetry by accident, this would be the 'the more frequent the better' theory (thanks to [Florian Jaeger](http://www.bcs.rochester.edu/people/fjaeger/) for discussion of this). Maybe this could account for why English traditionally has used rhyme less. That theory would predict that rhymes over all are less satisfactory in English, which might be hard to test. Also in that theory, it is not clear that why there is such a sharp divide between non-identical rhymes and identity rhymes in English.

Maybe there are finer grained distinctions to be made depending on the cohort-size of a particular word. A rhyme could be better if there are not too many cohort-mates. [Luc Baronian](http://www.uqac.ca/~baronian) suggested to us that maybe if there are too few cohort-mates, this might have an adverse effect on the quality of the rhyme as well.

Lev Blumenfeld suggested to us that words ending in open syllables might be more frequent in French, and for those more material than just the rhyme is incorporated in the rhyme domain, simply because the rhyme is otherwise not similar enough. This would make interesting predictions for how well identity rhyme is rated depending on the syllable structure of the words in question.

One way to test these hypotheses is to do further cross-linguistic comparisons of how rhyme is used and how rhyming resources are distributed in the lexicon. Another way would be to manipulate cohort-size within language, and look at how rhymes are rated depending on cohort-size. Also, we haven't yet computed the lexical stats for rime riche--which might further support or disconfirm various of these hypotheses. One interesting observation is that in our Wilhelm Busch samples, homophones in French are more frequent in the identity rhymes than the lexical statistics would predict them to be (at least according to our crude numbers), suggesting that there is no penalty in French even for complete phonological identity.

We have to play more with the way we count rhymes, e.g., we haven't controlled for various potential issues that Mark discusses. We were less concerned with entries in the lexicon that were separated by white space, that is, multiple word entries. since 'mosaic rhymes', that is, rhymes that span a word boundary, it seems to us, are quite acceptable. Morphological identity is also bound to play a role. While in our experiments, we didn't find an effect of morphological identity of stems, it's likely (and often noted in discussion of poetry) that at least homoeoteleuton might be less satisfactory as rhymes.

One factor that is probably very important but we haven't considered yet is that the frequency of the words in a cohort might make cohort-mates more or less relevant.

Many things remain to be done, but based on what we've found so far it seems to me that our explanation for the restriction against identity rhymes based on information structure is still standing: It's the only account as far as I can see that makes a clear prediction about the status of identity rhyme in the two languages.

[added some rhyme counts, homophone stats, and made minor corrections on dec 26; added more rhyme counts on jan 16 '10]

