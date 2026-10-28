---
author: Bianca Kramer
categories:
date: "2026-10-26"
draft: false
excerpt: "Review for MetaROR of 'Market dynamics, governance and open research metadata in the AI era' (2026)."
layout: single
subtitle: 
title: "Journal lists in OpenAlex - mixed feelings "

---
  
[![](202610_journal_lists_in_openalex_1.png)](https://metaror.org/article/market-dynamics-governance-and-open-research-metadata-in-the-ai-era/)

## Journal lists in OpenAlex
[OpenAlex](https://openalex.org) shared a blog post last week about their implementation of journal lists: https://blog.openalex.org/trusted-journal-lists-come-to-openalex/. OpenAlex previously had '*in_scopus*' as a variable (which is no longer available) as well '*in_core*' to indicate inclusion in the 'core journal list' from the Leiden Ranking (Open Edition). Since September 2026, coverage has been extended to include first 22 and now 61 journal lists of all stripes.

## What to think?
Personally, I am of two minds about this - on one hand, having this information available as open data, and made interoperable with the other data in OpenAlex, is useful and meeting a need that has been articulated often by users. Also, the fact that OpenAlex implements a broad set of lists (including e.g. LatIndex, SciELO and AJOL) does allow people to take their own responsibility for what they choose to use, shows the diversity in indexes/journal lists, and can help expand the concept of 'visibility' beyond 'included in Web of Science or Scopus'.

On the other hand, OpenAlex positions this as a trust signal, which I think can be problematic, and mixes different types of lists, which compounds the issue - crucially including many national research evaluation lists.

## Mixed messaging  
In the blog post, it is claimed that '*allow lists*' (whitelists by any other name :rose:) are the preferred approach to assess the 'trustworthiness' of a journal. Ironically, [ThinkCheckSubmit](https://thinkchecksubmit.org/journals/) is quoted to justify this, which instead advocates assessment at journal level, and does not mention or advocate using whitelists as proxies.

More importantly, the inclusion of national research evaluation lists mixes (proxy) assessment of trustworthiness with assessment of prestige. The use of such lists for decisions on funding and evaluation goes directly against [DORA](https://sfdora.org/). The inclusion of them as proxies of trustworthiness is questionable in my opinion, and it could be argued that the inclusion of these lists further entrenches the use of journal lists in research assessment.

## Where does responsibility lie?
Of course it can be argued that OpenAlex' role is not to explicitly support responsible research evaluation, and that, in their words 'Judgment stays with the people who made the list", as well as those that use the list(s).

I am broadly suportive of that from an open research information perspective. However, I do think that the use of journal list still deserves critical reflection and that it is important to be aware of the nature and purpose of various lists, and how that affects their inclusion criteria. OpenAlex takes on some responsibility on this when they integrate these lists - and could, for example, include such information, either as a list typology or by including a list's own description as a variable in the source list entity. 


#### About the author:
*The author of this response is independent advisort and research analyst at Sesame Open Science (working in the areas of open science, open metadata and open infrastructure) as well as Executive Director of the Barcelona Declaration on Open Research Information. This response is written in a personal capacity, representing my personal views and opinions.*


