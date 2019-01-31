# HateBrain v2.0

```Deployed November 2018

## Features

### Probability-Based Weighted Assessment

Unlike the previous version of HateBrain, which generated a binary result, this version returns a probability estimate that the context of the submitted post is hate speech.

The probability algorithm takes numerous factors into account, including multiple usages of hate speech within a single post, the presence of inflammatory language and other "pilotfish" (see below), and the known history of the content creator.

### Improved Geolocation

This version of HateBrain employs an enhanced mapping tool (HateMap) which significantly increases the system's ability to associate content with location by doing keyword analysis of content creator profiles.

### Pilotfish

The previous version of HateBrain used several types of corollary language (now called "pilotfish") to assess whether a given term is being used in a hate speech context. The number and variety of these pilotfish have significantly increased.

### Language-Matching

To help reduce false positives due to homonyms in other languages, HateBrain now performs language detection with a high level of success for posts of over 50 characters.

### Multilingualism

The terms that HateBrain searches for, and the pilotfish that HateBrain employs in its analysis, are increasingly multilingual, and contain both Latin and non-Latin character sets.

## Further reading

* [Getting Started with the Hatebase API 4.0](https://thesentinelproject.org/2018/12/11/getting-started-with-the-hatebase-api-v4-0/)
