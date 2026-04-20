# Summary

UD_Balochi-GPS is a treebank of the Balochi language variety spoken in southeastern Iran annotated according to the Universal Dependencies framework.


# Introduction

UD_Balochi-GPS is a manually annotated treebank for the Balochi language. The data comes from the GPS collection of traditional Balochi folk narratives. The texts are of the fiction/narrative genre and contain dialogue, storytelling, and descriptive prose.

The annotation follows the Universal Dependencies guidelines and covers tokenization, lemmatization, morphological features (including number, person, tense, aspect, mood, voice, and pronoun type), part-of-speech tags (UPOS), and syntactic dependency relations. All annotation was performed manually by human annotators.

Each sentence is identified by a sentence ID of the form `blc_gps-N`, where N corresponds to the sentence's position in the original source. English glosses are provided for each sentence via the `# text_en` comment field.

The dataset is split into training, development, and test sets as follows:

- Training: 240 sentences, 832 tokens
- Development: 30 sentences, 112 tokens
- Test: 30 sentences, 104 tokens

The three splits were created by random sampling from the full sentence pool. Sentences across all splits are drawn from the same single source collection and are not grouped by document or story chapter.

The treebank consists of isolated sentences drawn from a single narrative collection. All sentences belong to the fiction genre as classified under UD conventions. Genre can be identified via the sentence ID prefix `blc_gps`.


# Acknowledgments

...

## References

* Barjasteh Delforooz, B. (2010). Discourse Features in Balochi of Sistan: (Oral Narratives). (Doctoral dissertation). Uppsala: Acta Universitatis Upsaliensis

# Changelog

* 2026-05-15 v2.18
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.18
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: Oral Narratives
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Asadpour, Hiwa; Verkerk, Annemarie; Afzal, Muhammad
Contributing: here
Contact: Asadpourhiwa@gmail.com
===============================================================================
</pre>
