---
layout: project
title: Find
project-type: UX, Research
---

# Search UX for Rhapsody Music
---
## Findability

A challenge for any interface dealing with a deep amount of content is findability. On streaming music services, the findability of content typically reflects on how well the service executes in two areas:

  * Search: The benchmark answer to findability is the search box. The familiar escape hatch that any person who knows how to “Google it” can use. Not only is search expected, but it is expected to be nearly instantaneous.
  * Browse: Users also expect to find content via browsing, whether that means browsing socially via user profiles, on curated pages, through “related” content, or otherwise.

<img src="{{ site.baseurl }}/images/find/apple-music-search.jpg" alt="search on apple music">
<img src="{{ site.baseurl }}/images/find/spotify-browse.jpg" alt="browse on spotify">


## Coexisting Modalities

Search and Browse are modalities of finding content that coexist in parallel, working together by complimenting each other’s faults. <em>Search</em> requires that we know what we want and have the words to describe our needs, while <em>Browse</em> presents content in front of us, revealing what's available.

What if there was way both modalities could coexist not only in parallel, but intertwined? — What is a unified search + browse feature?

## Stepping Back

In <a href="http://searchpatterns.org/" target="_blank"><em>Search Patterns: Design for Discovery</em></a>, Peter Morville & Jeffery Callender describe that when large sites scale, traditional means of browsing inevitably fail to support the chaotic sprawl of content that emerges. At that point, they identify three key areas with the potential to act as powerful fulcrum on which to design for findability:

<figure>
  <img src="{{ site.baseurl }}/images/find/three-fulcra.jpg" alt="the three fulcra of large websites">
  <figcaption>Three fulcra of large websites, from “Search Patterns: Design for Discovery”, Peter Morville & Jeffery Callender</figcaption>
</figure>


Using this model as basic infrastructure, we design each fulcra in support of the other two, with an eye towards creating a sense of flow. Some key principles:

### Portal (The UI)
  * Usability: leveraging existing design patterns
  * Enabling multiple paths to the content people are looking for

### Search
  * Speed: creating an iterative, interactive experience that operates as fast as the user can think
  * Being able to fluidly move between searching the site to searching specific facets of content

### Objects: Adopting best practices in SEO
  * Designing objects to be destinations
  * Designing objects to be social, subjects of conversation
  * Designing objects to be gateways to related content

---

> …having identified the objects plus the portal and search as strategic opportunities where leverage affords impact, the trick is weaving them together so that each element becomes a vital part of the whole.

— Moreville & Callender

How can this be achieved?

---

## Collections

<img src="{{ site.baseurl }}/images/find/collections.jpg" alt="collections">

<em>Find</em> hinges around this idea of creating a virtuous cycle between the three fulcra of a music streaming service by introducing a term borrowed from the Search Patterns book: Collections.

<em>Collections</em> as the word suggests, are simply the groupings of content and information on a site as made by:

  * A traditional tagging system
  * #hashtags from users
  * The information architecture of the site
  * Metadata (e.g. year, label, country)

But more importantly:

  * Collections are <strong>facets of content</strong> by which users can <strong>filter</strong>, <strong>search</strong> and <strong>browse</strong>.

## Collection Browser

The first place collections are introduced is front and center in our UI. Adjacent to the search field, collections are presented in the form of a swipe-able collection browser.

<img src="{{ site.baseurl }}/images/find/collection-browser.gif" alt="collection browser">

### Interacting With collections

When we tap a collection, as expected, the associated content is presented to us. However, we remain in a search context, because collections are not only facets of content we can browse, but facets of content that we can narrow our search by:

<img src="{{ site.baseurl }}/images/find/collection-interaction.gif" alt="collection interaction">

Using the Collection Browser, we can then further refine searches, and reveal relationships that were previously invisible:

<img src="{{ site.baseurl }}/images/find/combine-tags-jazz+fusion.gif" alt="combining jazz + fusion tags">

## Search

We’ve already seen how collections can augment our searches, but we must be able to find collections without having to rely on the collection browser. When we know what we want, typing into the search box should do what we expect and reveal what we are looking for.

When considering instant search results as we type, we generally are speaking of these two subtly different user interfaces: <em>auto-complete</em> & <p>auto-suggest</p>

<figure>
  <img src="{{ site.baseurl }}/images/find/appleMusic_autocomplete.gif" alt="auto-complete on apple music">
  <figcaption>Auto-complete resolves partial search terms helping us craft better queries. (Auto-complete on Apple Music)</figcaption>
</figure>

<figure>
  <img src="{{ site.baseurl }}/images/find/napster_autosuggest.gif" alt="auto-suggest on rhapsody music">
  <figcaption>Auto suggest brings user to content faster by eliminating the need to perform a search query (Auto-suggest on Rhapsody)</figcaption>
</figure>

Streaming music services tend to lean towards auto-suggest for good reason. It provides the fastest route to music possible. Algorithms are good enough that the top result will be the right result, most of the time. A key benefit of auto-suggest—and important for the <em>Find</em> model— is that content is immediately visible. In this sense, the UI is already conducive to browsing.

We can maintain this browsing friendly UI and enable directed searches for our collections by using a hybrid model. As we type into the search box, matching collections appear where they normally do, with our suggested results appearing below that:

<img src="{{ site.baseurl }}/images/find/collection-search.gif" alt="collection search">

## Objects

Finally, the virtuous cycle can be made complete using the collections model to explore related content through facets exposed on the objects themselves:

<img src="{{ site.baseurl }}/images/find/object-to-find.gif" alt="from object to find">

In this way, the objects not only serve as the content, but as a means of finding; illuminating relationships, and opening infinite pathways to navigate the sprawl of content that is so common on large sites today.

[Framer prototype](http://share.framerjs.com/pdwq9lxp4rya/) (best viewed in Safari)
