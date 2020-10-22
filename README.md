# Summary

UD Indonesian-CSUI is a conversion from an Indonesian constituency treebank in the Penn Treebank format named [**Kethu**](https://github.com/ialfina/kethu) that was also a conversion from a constituency treebank built by [**Dinakaramani et al. (2015)**](https://github.com/famrashel/idn-treebank). We named this treebank **Indonesian-CSUI**, since all the three versions of the treebanks were built at Faculty of Computer Science, Universitas Indonesia.


# Introduction

UD Indonesian-CSUI treebank was converted automatically from the **Kethu** treebank, an Indonesian constituency treebank in the Penn Treebank format. The Kethu treebank itself was converted from a consituency treebank built by [**Dinakaramani et al. (2015)**](https://github.com/famrashel/idn-treebank). 

Other characteristics of the treebank:
* This treebank consists of 1030 sentences and 28K words. We devide CSUI treebank into testing and training dataset:
  * Testing dataset consist of around 10K words
  * Training dataset consist of around 18K words
* The genre of the sentences are mainly news in formal Indonesian. 
* Average sentence length is around 27.4 words per-sentence, which is very high compare to the [Indonesian-PUD](https://github.com/UniversalDependencies/UD_Indonesian-PUD) treebank that has average sentence length of 19.4.
* Current version has no lemma and morphological features.


# Acknowledgments

* The original constituency treebank was built with manual annotation by [Arawinda Dinakaramani, Fam Rashel, Andry Luthfi, and Ruli Manurung](https://github.com/famrashel/idn-treebank) at Faculty of Computer Science, Universitas Indonesia in 2015.
* The previous treebank was converted to the Penn Treebank format by Ika Alfina and Jessica Naraiswari Arwidarasti at Faculty of Computer Science, Universitas Indonesia in 2019-2020. This PTB version was named [**Kethu**](https://github.com/ialfina/kethu).
* The Kethu treebank was converted to a UD treebank by Ika Alfina et al. in 2020.

## References
* Ika Alfina, Indra Budi, and Heru Suhartanto. "**Tree Rotations for Dependency Trees: Converting the Head-Directionality of Noun Phrases**". In Journal of Computer Science (_accepted_)


# Changelog

* 2020-11-15 v2.7
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.7
License: CC BY-SA 4.0
Includes text: yes
Genre: nonfiction news
Lemmas: not available
UPOS: converted from manual
XPOS: manual native
Features: not available
Relations: converted from manual
Contributors: Alfina, Ika; Arwidarasti, Jessica Naraiswari;  Dinakaramani, Arawinda; Manurung, Ruli; Rashel, Fam; Luthfi, Andry 
Contributing: elsewhere
Contact: ika.alfina@cs.ui.ac.id
===============================================================================
</pre>
