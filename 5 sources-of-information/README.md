# Sources of information

Information on sources of information can be found in the Editorial Guide on the following webpages:

* [Organism Naming Conventions](https://confluence.ihtsdotools.org/display/DOCEG/Organism+Naming+Conventions)
* [US vs. GB English](https://confluence.ihtsdotools.org/display/DOCEG/US+vs.+GB+English)
* [Antibodies and antigens](https://confluence.ihtsdotools.org/display/DOCEG/Antibodies+and+antigens)
* [Antivenom](https://confluence.ihtsdotools.org/display/DOCEG/Antivenom)

In addition, NRCs should create and maintain a document that specifies which sources are authoritative and should accompany the translation process so that all translators involved have a common basis for determining which sources are acceptable. Translators and other professionals involved in the translation process should also have access to a range of reliable and recognised sources of information in their own language. Both external and internal sources can be used. For example, the Dutch NRC uses the following external sources:

* Pinkhof Geneeskundig woordenboek (Pinkhof medical dictionary)
* Terminologia anatomica ([https://www.anatomicalterms.info/)](https://www.anatomicalterms.info/\))
* the same thesauri for organisms as given by SNOMED International in the Editorial Guide
* Orphanet (the quality of translation can be questionable, but it is often the only source for a rare disease)
* Farmacotherapeutisch kompas (for substances)
* the archive of the _Nederlands Tijdschrift voor Geneeskunde_ (NTvG) (Dutch Journal of Medicine)

The following internal sources are used:

* a self-created Java API that suggests possible translations based on the concept definition (only for concepts that meet certain criteria, e.g. are fully defined)
* a spell checker that incorporates the Pinkhof Geneeskundig woordenboek (Pinkhof medical dictionary)
* indexed comments logged for each previous translation
* guidelines agreed during the translation project, both general and specific phrases
* recorded discussions on proposed guidelines (so that the rationale for a guideline can be looked up or it can be checked whether a guideline was considered but rejected)
* previous translations, for consistency

For reasons of lack of quality, the Dutch translation of ICD-10 or ICPC is deliberately not used.

In addition to sources in the local language, English sources can also be useful in determining the exact nature and meaning of a term.

Wherever possible, selected internal working documents, textbooks, reference works, etc. should be directly accessible in electronic form for anyone to find information on a particular concept by means of text examples, definitions or expressions containing a particular word or phrase.

Machine translation systems such as Google Translate and DeepL or online translation tools such as eTranslation ([https://ec.europa.eu/cefdigital/wiki/display/CEFDIGITAL/eTranslation](https://ec.europa.eu/cefdigital/wiki/display/CEFDIGITAL/eTranslation)) can be a potential help, but should be used with caution. Currently, the accuracy of translation is not yet sufficient to translate clinical content with the exactness required from a clinical risk perspective. However, MT can be helpful in providing an initial translation that can then be reviewed; or it can be limited to template concepts.

In the following sections relevant existing electronic information sources and internet references (Section [#electronic-information-sources-and-internet-references](./#electronic-information-sources-and-internet-references "mention")) are listed, followed by an overview of sources that can be created by means of corpus tools or automated suggestions (Section [#id-5.2-self-created-corpora](./#id-5.2-self-created-corpora "mention")). It is advisable to check the validity and quality of each source, especially the national editions of international sources.

## Electronic information sources and internet references

Section 4.4.2.1 Organism names (bacteria, viruses, plants, animals, etc.) already contains a list of specific resources for bacteria, viruses, parasites, etc.. The following additional sources may also be helpful:

**Ready access to already approved, translated terms**

* It should be possible for translators and other persons involved in the translation process to refer to previously approved terms containing similar constructions and/or word combinations.

**Online dictionaries and databases**

* _Dictionnaire médical de l'Académie de Médecine_ – version 2022 ([http://dictionnaire.academie-medecine.fr/index.php](http://dictionnaire.academie-medecine.fr/index.php))
* _Oxford Concise Medical Dictionary_ (10de edition). (2020). Oxford University Press. ([https://doi.org/10.1093/acref/9780198836612.001.0001](https://doi.org/10.1093/acref/9780198836612.001.0001))
* IATE (Interactive Terminology for Europe) ([https://iate.europa.eu/home](https://iate.europa.eu/home))
* WordNet ([http://globalwordnet.org/resources/wordnets-in-the-world/](http://globalwordnet.org/resources/wordnets-in-the-world/))
* info (ATI) ([https://www.anatomicalterms.info/](https://www.anatomicalterms.info/))

**National corpora**

**Internal working documents** such as:

* national guidelines for translation
* overview of the principle decisions of the Editorial Board or a similar competent body
* lists of examples of translated terms and/or corrected terms representing specific semantic or morphosyntactic features

**Textbooks** on the different areas of clinical practice

**Reference files or books** such as:

* national versions of medical dictionaries or lexicons
* national version of the chemistry nomenclature
* national version of _Nomina Anatomica, Terminologia Anatomica_ or other nomenclatures
* national version of the _International Classification of Diseases_ (ICD-11)
* national versions of other classifications

**Explorative resources**

These sources should be used with care and serve as inspiration, but not as an authoritative source as they contain, for example, synonyms that are not entirely interchangeable or outdated terminology and the like. Examples are:

* Wikipedia
* Pubmed ([https://pubmed.ncbi.nlm.nih.gov/)](https://pubmed.ncbi.nlm.nih.gov/\))
* MeSH ([https://www.ncbi.nlm.nih.gov/mesh/)](https://www.ncbi.nlm.nih.gov/mesh/\))
* Orphanet ([https://www.orpha.net/consor/cgi-bin/index.php?lng=EN](https://www.orpha.net/consor/cgi-bin/index.php?lng=EN))
* OMIM® (Online Mendelian Inheritance in Man®) ([https://www.omim.org/](https://www.omim.org/))
* INN (International Nonproprietary Names) ([https://www.who.int/teams/health-product-and-policy-standards/inn](https://www.who.int/teams/health-product-and-policy-standards/inn))
* com: to search in multiple English dictionaries ([https://www.onelook.com/reverse-dictionary.shtml](https://www.onelook.com/reverse-dictionary.shtml))

**Medical publications**

* electronic versions of articles from renowned national medical journals (these can be valuable references for the use of specific terms and abbreviations of foreign and local origin. It should be noted, however, that the expressions chosen in these journals may not always be linguistically correct or consistent if they are foreign language expressions. One should also consider the publication date, as terminology may have changed following new discoveries or techniques).
* clinical guidelines and quality assessment documents
* medical protocols
* national standardised guidelines for procedures

**Recommended internet references**

* A list of valid internet references with useful information should also be established. The recommended resources can be found in the Editorial Guide (see list of webpages at the beginning of chapter 5). Some relevant taxonomies or nomenclatures in English may be available in the target language.

## Self-created corpora

**Online tools**

* The Sketch Engine ([http://www.sketchengine.co.uk/](http://www.sketchengine.co.uk/))
* CLaRK ([http://www.bultreebank.org/clark/](http://www.bultreebank.org/clark/))
* CorpusExplorer ([http://www.CorpusExplorer.de](http://www.corpusexplorer.de))
* AntConc ([http://www.antlab.sci.waseda.ac.jp/software.html](http://www.antlab.sci.waseda.ac.jp/software.html))
* CoCab ([http://chasen.aist-nara.ac.jp/\~kaoru-ya/cocab/](http://chasen.aist-nara.ac.jp/~kaoru-ya/cocab/))

**Automated suggestions**

* a self-created Java API that suggests possible translations based on the concept definition (only for concepts that meet certain criteria, e.g. are fully defined)
* spell checkers that incorporate national medical dictionaries
* indexed comments logged for each previous translation in an online translation environment
* guidelines agreed during the translation project, both general and specific phrases
* recorded discussions on guidelines proposals
* previous translations, for consistency
* lexicon-based translation tools such as CoMeTT, used by the Belgian CSCT (for a detailed description see Wermuth, M.-C., Walravens, M., & Lambot M.-A. (2022). Collaboration and communities of practice in the field of medical ontology translation. (P. Cadwell, F. Federici, & S. O’Brien, Eds.) _The Journal of Specialised Translation_(37), 75-98).






<a href="https://docs.google.com/forms/d/e/1FAIpQLScTmbZIf0UEQwYDkY27EEWBkaiYkHSbR0_9DmFrMLXoQLyL7Q/viewform?usp=pp_url&entry.1767247133=Translation+Guide&entry.670899847=Sources%20of%20information" class="button primary">Provide Feedback</a>
