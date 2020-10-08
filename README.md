# Summary

UD Indonesian-CSUI is a conversion from an Indonesian constituency treebank in the Penn Treebank format named [**Kethu**](https://github.com/ialfina/kethu) that was also a conversion from a constituency treebank built by [**Dinakaramani et al. (2015)**](https://github.com/famrashel/idn-treebank). 
We named this treebank **Indonesian-CSUI**, since all the three versions of the treebanks were built at Faculty of Computer Science, Universitas Indonesia.


# Introduction

UD Indonesian-CSUI treebank was converted automatically from the **Kethu** treebank, an Indonesian constituency treebank in the Penn Treebank format. This treebank consists of 1030 sentences and 28,228 words. The Kethu treebank itself was converted from a consituency treebank built by [**Dinakaramani et al. (2015)**](https://github.com/famrashel/idn-treebank) using a semi-automatic approach. The bracketing conversion to the PTB format was automatic, but the revising of word segmentation, POS tagging and some syntactic annotations was done manually.

Other characteristics of the treebank:
* The genre of the sentences are mainly news in formal Indonesian. 
* Average sentence length is around 27 words per-sentence, which is very high compare to the [Indonesian-PUD](https://github.com/UniversalDependencies/UD_Indonesian-PUD) treebank that has average sentence length of 19.4.


# Acknowledgments

* The original constituency treebank was built with manual annotation by [Arawinda Dinakaramani, Fam Rashel, Andry Luthfi, and Ruli Manurung](https://github.com/famrashel/idn-treebank) at Faculty of Computer Science, Universitas Indonesia in 2015.
* The idn-treebank was converted to the Penn Treebank format by Ika Alfina and Jessica Naraiswari Arwidarasti at Faculty of Computer Science, Universitas Indonesia in 2019. This PTB version of the _idn-treebank_ was named [**Kethu**](https://github.com/ialfina/kethu).
* The Kethu treebank was converted to a UD treebank by Ika Alfina and Jessica Naraiswari Arwidarasti in 2020.

## References
* Ika Alfina, Indra Budi, and Heru Suhartanto. "**Tree Rotations for Dependency Trees: Converting the Head-Directionality of Noun Phrases**". In Journal of Computer Science (_accepted_)
* Jessica Naraiswari Arwidarasti, Ika Alfina, and Adila Alfa Krisnadhi. ["**Converting an Indonesian Constituency Treebank to the Penn Treebank Format**"](https://ieeexplore.ieee.org/abstract/document/9037723). In the Proceeding of The 2019 International Conference of Asian Language Processing (IALP 2019) in Shanghai, China, 15-17 November 2019. 


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
