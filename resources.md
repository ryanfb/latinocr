---
title: Latin OCR Development Resources
---

# [Latin OCR]({{ site.baseurl }}/) Development Resources

## Corpora & wordlists:

 * [**Perseus**](http://www.perseus.tufts.edu/hopper/opensource/download)
   * 240,000 attested words, 49,000 lemmata, manually-entered editions
 * [**Bruce Robertson's Rigaudon dictionary**](https://github.com/brobertson/rigaudon/blob/master/Dictionaries/greek_and_latin.txt)
   * 693,000 attested words, [Latin from Uwe Springmann](https://twitter.com/heml/status/537057040351244288)
 * [Open Greek and Latin Project](https://github.com/OpenGreekAndLatin)
   * Machine-corrected versions of [Lace](http://heml.mta.ca/lace) OCR output
 * [Lace](http://heml.mta.ca/lace)
   * Raw OCR output of Rigaudon (Gamera-based process)
 * [David Bamman: 11K Latin Texts](http://www.cs.cmu.edu/~dbamman/latin.html)
   * 3.9GB compressed, 11,261 texts, 1.38 billion tokens, OCR-derived
 * [CAMENA (Corpus Automatum Multiplex Electorum Neolatinitatis Auctorum)](https://github.com/nevenjovanovic/camena-neolatinlit)
   * 50M words
 * [Words program of the late William Whitaker](http://archives.nd.edu/whitaker/words.htm)
   * 1M word forms derived from 39,000 lemmata
 * [Spell checking lexicon for OpenOffice/LibreOffice constructed by Karl Zeiler](http://extensions.openoffice.org/en/project/latin-spelling-and-hyphenation-dictionaries)
   * 129,000 word forms
 * [Latin words in the English Wiktionary](http://dsh.oxfordjournals.org/content/early/2015/03/29/llc.fqv008)
   * 655,434 word forms for 32,860 roots
 * Springmann et al. canonical lexicon (forthcoming?)
   * 2M word forms, 70,000 lemmata
 * [Bibliotecha Latina IntraText](http://www.intratext.com/LATINA/)
 * [CLTK](https://github.com/kylepjohnson/cltk) corpora
   * [The Latin Library](https://github.com/cltk/latin_corpus_latin_library) - 108MB
   * [LacusCurtius](https://github.com/cltk/latin_corpus_lacus_curtius) - 28MB (HTML)
   * [Latin proper names](https://github.com/cltk/latin_proper_names) - ~40K proper names
 * [Pleiades](http://pleiades.stoa.org/) - [22,140 Latin place names](https://github.com/ryanfb/latinocr-lattraining/commit/29b71a03840080e1fc679a8c992001257dcf2a73)
 * [Johann Ramminger's Neulateinische Wortliste (Neolatin wordlist)](http://www.neulatein.de/)
   * "The NLW now contains 19225 lemmas with 1928 Variants [...] The *Sigelliste* of NLW contains 2675 authors and 7402 works abbreviations."
 * [Bibliotecha Augustana](http://www.hs-augsburg.de/~harsch/augustana.html#la)
 * [Musisque Deoque](http://www.mqdq.it/mqdq/home.jsp?lingua=en) and [Poeti d'Italia](http://www.mqdq.it/mqdq/poetiditalia/home.jsp?lingua=en)
 * [Corpus Grammaticorum Latinorum (CGL)](http://kaali.linguist.jussieu.fr/CGL/text.jsp)
 * [Corpus Thomisticum](http://www.corpusthomisticum.org/)
 * [Croatiae auctores Latini (CroALa)](https://jtei.revues.org/425)
 * [Index Thomisticus Treebank](http://itreebank.marginalia.it/)
   * 263,425 tokens
 * [The PROIEL Treebank](https://github.com/proiel/proiel-treebank)
   * 146,892 Latin words
 * [The Ancient Greek and Latin Dependency Treebanks](http://nlp.perseus.tufts.edu/syntax/treebank/latin.html)
   * 53,143 Latin words
 * [Integrating Digital Papyrology (IDP)](https://github.com/papyri/idp.data)
 * See also: [Digital Critical Editions of Texts in Greek and Latin](https://wiki.digitalclassicist.org/Digital_Critical_Editions_of_Texts_in_Greek_and_Latin)

## Related projects & other efforts:

 * [*OCR of Historical Printings of Latin Texts: Problems, Prospects, Progress*](http://www.cis.uni-muenchen.de/~springmann/papers/2014-04-07-DATeCH2014-Springmann.pdf), Springmann et al., 2014
   * [Talk](http://vimeo.com/99220359), [Slides](http://www.cis.uni-muenchen.de/~springmann/acroases/2014-05-20-Madrid.pdf)
 * [*Improving OCR Accuracy for Classical Critical Editions*](http://link.springer.com/chapter/10.1007/978-3-642-04346-8_17), Boschetti et al., 2009
 * [Himeros.eu Latin OCR Trainings for Tesseract](http://www.himeros.eu/), Boschetti, 2008
   * Based on 5 pages of a [1475 incunabular edition of Augustine's *De civitate Dei*](https://archive.org/details/augustinidecivitatedei00jensuoft)
 * [*A Document Recognition System for Early Modern Latin*](http://dl.tufts.edu/catalog/tufts:PB.001.001.00021), Sravana & Crane, 2006
   * Based on Gamera and Perseus

## Other related links:

 * [McGillivray, Barbara. *Methods in Latin Computational Linguistics*. Leiden: Brill, 2014.](http://www.worldcat.org/title/methods-in-latin-computational-linguistics/oclc/868040419)
 * [eMOP: Early Modern OCR Project](http://emop.tamu.edu/)
   * [Special Characters, Unicode, and Early Modern English](http://emop.tamu.edu/node/53)
   * [PRImA Research Tools](http://www.primaresearch.org/tools)
 * [*Towards a Network Model of the Coreness of Texts: An Experiment in Classifying Latin Texts Using the TTLab Latin Tagger*](http://link.springer.com/chapter/10.1007/978-3-319-12655-5_5), Mehler et al., 2014
 * [*On OCR ground truths and OCR post-correction gold standards, tools and formats*](http://dl.acm.org/citation.cfm?id=2595216), Reynaert, 2014
 * [*PoCoTo - an open source system for efficient interactive postcorrection of OCRed historical texts*](http://dl.acm.org/citation.cfm?id=2595197), Vobl et al., 2014
 * [*A Fast Alignment Scheme for Automatic OCR Evaluation of Books*](http://dx.doi.org/10.1109/ICDAR.2011.157), Yalniz & Manmatha, 2011
 * [*OCR and the transformation of the Humanities*](https://impactocr.wordpress.com/2011/10/25/keynote-ocr-and-the-transformation-of-the-humanities-2/), Crane, 2011
 * [*Digitizing Latin Incunabula: Challenges, Methods, and Possibilities*](http://digitalhumanities.org/dhq/vol/3/1/000027/000027.html), Rydberg-Cox, 2009
 * [*Automatic disambiguation of Latin abbreviations in early modern texts for humanities digital libraries*](http://dl.acm.org/citation.cfm?id=827207), Rydberg-Cox, 2003

## Non-Free Corpora

 * Library of Latin Texts (LLT), Brepols
 * Thesaurus linguae Latinae (TLL), De Gruyter
 * [PHI Latin Texts](http://latin.packhum.org/)
 * Bibliotheca Teubneriana Latina (BTL)
 * [LatinWordNet](http://catalog.elra.info/product_info.php?products_id=1098)
