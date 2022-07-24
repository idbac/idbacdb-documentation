---
layout: default
title: Quickstart Search
nav_order: 3
---

## Quickstart Search Guide

To begin searching IDBacDB simply select the "Spectrum Search" link on the homepage:

![Search Home Page]({{'assets/images/spectrum-search-homepage.png' | relative_url}})

On the following page you will presented with a single text input field which allows you to fill in a mass list to query against
all spectra in public libraries. (_Note: private library group searches will be enabled in the near future._) Your mass list must
be composed on only numerical values, with a single mass value per line.

A sample mass list can be found [here on our public sample drive](https://drive.google.com/file/d/16Gg5lrAoki5W3XxkpA5sxKJ1dZt6IBlE/view).
Simple copy and paste the contents of this file into the input box as show and press submit:

![Search Masslist]({{'assets/images/spectrum-search-masslist.png' | relative_url}})

Submitting your mass list will add your search to server and will return a result in short time:

Results will look as follows:

![Search Results]({{'assets/images/spectrum-search-results.png' | relative_url}})

You can review the matching score from your submitted masslist, as well as compare the 
spectrum of your masslist to the library spectrum. By default the top scoring spectrum will be rendered below,
but simply press the __preview__ icon next to the "Spectrum ID" to compare that spectrum to your own mass list.

More details about the scoring algorithm can be found in our [Spectrum Search Docs]({{'/idbacdb/spectrum-search' | relative_url}})