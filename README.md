# Summary

UD\_Old\_East\_Slavic-TOROT is a conversion of a selection of Old East Slavonic and Middle Russian data from the Tromsø Old Russian and OCS Treebank (TOROT), which was originally annotated in PROIEL dependency format.

# Introduction

UD Old East Slavic TOROT is a conversion of a selection of  Old East Slavonic and Middle Russian data from the Tromsø Old Russian and OCS Treebank (TOROT), which was built at UiT The Arctic University of Norway and is now maintained at the University of Oslo. The treebank is manually annotated, with some automatic preprocessing, on PROIEL dependency format. New texts are still being added. The treebank contains texts from a variety of mediaeval and early modern genres, such as chronicles, legal documents, lives of saints and correspondence. The original treebank files are available fromhttps://github.com/syntacticus/syntacticus-treebank-data. The current conversion is based on the 20230428 release. The conversion code was written by Dag Haug and Hanne Eckhoff and is available in the Rubygem proiel-cli, available at https://github.com/proiel/proiel-cli

# Data splits

The development set consists of Afanasij Nikitin 12–13; birchbark letters 502 and 531; the colophon to Mstislav's Gospel book; Domostroj 22–25; Life of Sergij of Radonezh 19; Russkaja pravda 52-58; Novgorod First Chronicle (Synodal ms.) s.a. 6736–6738; Vladimir Monomakh's Instruction; Life of Avvakum 11–14; Suzdal Chronicle (Laurentian ms.) s.a. 6656–6658; The Tale of Dracula; The Tale of Igor's Campaign; Tale of the Fall of Constantinople, chapter 6; Uspenskij sbornik, Life of Feodosij Pečerskij 25-27.

The test set consists of Afanasij Nikitin 18–19; birchbark letters 724, 725 and 731; the colophon to the Ostromir Codex; Domostroj 35–39; Life of Sergij of Radonezh 12; Life of Stefan of Perm, extract 1; Russkaja pravda 31–39; Novgorod First Chronicle (Synodal ms.), s.a. 6705–6712; Life of Avvakum 55–59; Primary Chronicle (Laurentian ms.), Introduction and s.a. 6494; Suzdal Chronicle (Laurentian ms.) s.a. 6655, 6659 and 6660; The taking of Pskov; Tale of the Fall of Constantinople, chapters 1-3; Uspenskij sbornik, Life of Feodosij Pečerskij 21-24 and 28.

The training set consists of larger, continuous excerpts from Afanasij Nikitin, Domostroj, Life of Sergij of Radonezh, Life of Stefan of Perm, Life of Avvakum, Russkaja pravda, Novgorod First Chronicle (Synodal ms.), Primary Chronicle (Laurentian ms. and Hypatian ms.), Suzdal Chronicle (Laurentian ms.), The Kiev Chronicle (Hypatian ms.), Tale of the Fall of Constantinople, Uspenskij sbornik, as well as a further selection of birchbark letters, a selection of charters, treaties and shorter chronicle texts, and the Zadonshchina.

# Acknowledgements

The texts were converted by Hanne Eckhoff. The texts were annotated and reviewed by a brilliant team of annotators, who are acknowledged in the original treebank files and who deserve to be thanked profusely.

## References

Hanne Martine Eckhoff and Aleksandrs Berdičevskis. 2015. 'Linguistics vs. digital editions: The Tromsø Old Russian and OCS Treebank'. Scripta & e-scripta 14–15, pp. 9-25.


# Changelog

* 2022-05-15 UD 2.10
  * MISC ref= changed to Ref= to match other UD treebanks.
* 2021-05-15 v2.8
  * Repository renamed from UD_Old_Russian-RNC to UD_Old_East_Slavic-RNC.
  * Undocumented feature Strength replaced with Variant=Short as in other Slavic treebanks.
  * Undocumented Aspect=Res converted to VerbForm=PartRes|Tense=Past as in the other orv treebank.
  * Negative copula не быти lemmatized as быти, added Polarity=Neg.
* 2019-05-15 v2.4
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.4
License: CC BY-NC-SA 4.0
Includes text: yes
Genre: nonfiction legal
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Eckhoff, Hanne
Contributing: elsewhere
Contact: hanne.eckhoff@mod-langs.ox.ac.uk
===============================================================================
</pre>
