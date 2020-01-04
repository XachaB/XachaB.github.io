---
---

My research in computational linguistics focuses on the typology of morphological structure.

During my PhD, I studied inflection classes (declensions or conjugations) and their typological variation. I am currently a post-doctoral researcher at the Max Planck Institute for the Science of Human History, in the department of Linguistic and Cultural Evolution in Jena, working on morphophonological evolution with [Erich Round](https://www.shh.mpg.de/person/98374/25522).

I see computational tools as an opportunity to systematize linguistic analyses, a solution to study precisely large amounts of data, and a necessary methodological step towards typological investigation. 

## Publications

<ul class="publications">
  <li>**Sacha Beniamine**, Martin Maiden, and Erich Round. “Opening the Romance Verbal Inflection Dataset 2.0: A CLDF lexicon”. Submitted to LREC 2020 <a href="/papers/BeniamineMaidenRound-LREC2020.pdf.pdf">[preprint pdf]</a>
    <blockquote>
        We introduce the Romance Verbal Inflection Dataset 2.0, a multilingual lexicon of Romance inflection covering 73 varieties. The lexicon provide verbal paradigm forms in broad IPA phonemic notation. Both lexemes and paradigm cells are organized to reflect cognacy. Such multi-lingual inflected lexicons annotated for two dimensions of cognacy are necessary to study the evolution of inflectional paradigms, and test linguist hypothesis systematically. However, these resources seldom exist, and when they do, they are not usually encoded in computationally usable ways. The Oxford Online Database of Romance Verb Morphology provides this kind of information, however, it is not maintained anymore and only available as a web service without interfaces for machine-readability. We collect its data and clean and correct it for consistency using both heuristics and expert annotator judgements. Most resources used to study language evolution computationally rely strictly on multilingual contemporary information, and lack information about prior stages of the languages. To provide such information, we augmented the database  with Latin paradigms from the LatInFlexi lexicon. Finally, to make it widely avalable, the resource is released under a GPLv3 license in CLDF format.
    </blockquote>
    </li>
    <li>Beniamine, Sacha. (in press) <b>“One lexeme, many classes: inflection class systems as lattices”</b> , In: <i>One-to-Many Relations in Morphology, Syntax and Semantics</i> , Ed. by Berthold Crysmann and Manfred Sailer. Berlin: Language Science Press. <a href="/papers/Beniamine2019.pdf">[preprint pdf]</a>
    <details markdown = "0">
        <summary markdown="0">[bib]</summary>
        <pre>@InBook{Beniamine2019,
          author    = {Sacha Beniamine},
          title     = {One lexeme, many classes: inflection class systems as lattices},
          booktitle = {One-to-Many Relations in Morphology, Syntax and Semantics},
          year      = {Forthcoming},
          editor    = {Berthold Crysmann and Manfred Sailer},
          publisher = {Language Science Press.},
          address   = {Berlin},
        }</pre>
    </details>
    <blockquote>
        Descriptions of inflection classes usually take the form of broad of fine-grained (Stump & Finkel 2013) partitions of the set of lexeme, or link both in a hierarchic system of classes
(Corbett & Fraser 1993; Dressler & Thornton 1996). Recent efforts to infer those automatically (Brown & Hippisley 2012; Lee
& Goldsmith 2013; Bonami 2014) all rely on the assumption that the hierarchy takes the shape of
a tree. We argue instead that  semi-lattices, in which multiple inheritance is possible, are more appropriate to the modelling of inflection class systems. They capture directly the phenomenon of heteroclisis (Stump
2006), where different aspects of a lexeme's paradigm relate it to different classes. 
We infer the semi-lattice using Formal Concept Analysis (Wille 1984) and describe a few measures of the canonicity of inflectional systems.
    </blockquote>
    </li>
    <li>Beniamine, Sacha. (2018) <b>“Classifications flexionnelles. Étude quantitative des structures de paradigmes.”</b> , Université Sorbonne Paris Cité - Université Paris Diderot (Paris 7), PhD thesis under the supervision of Olivier Bonami. <a href="https://tel.archives-ouvertes.fr/tel-01840448/document">[pdf]</a>
    <details markdown = "0">
        <summary markdown="0">[bib]</summary>
        <pre>@PhdThesis{Beniamine2018-PhD,
          author = {Sacha Beniamine},
          title  = {Classifications flexionnelles:
                    Étude quantitative des structures de paradigmes},
          school = {Université Sorbonne Paris Cité - Université Paris Diderot (Paris 7)},
          year   = {2018},
          note   = {PhD thesis under the supervision of Olivier Bonami},
          url    = {https://tel.archives-ouvertes.fr/tel-01840448},
          month  = Jul,
        }</pre>
    </details>
    <blockquote>This dissertation adopts the Word and Paradigm approach and elaborates computationaltools to investigate precisely the similarity structure of inflection class systems based on in-flectional lexicon. We study Arabic, Yaitepec Chatino, Zenzontepec Chatino, English, French,Navajo and European Portuguese verbs as well as Russian nouns.</blockquote>
    </li>
  <li>Sacha Beniamine, Olivier Bonami, and Joyce McDonough (2017). <b>“When segmentation helps. Implicative structure and morph boundaries in the Navajo verb”</b> . In: <em>First International Symposium on Morphology (ISMo).</em> Lille, France, pp. 11–15. <a href="https://colloque-ismo.univ-lille3.fr/data/documents/abstracts_booklet.pdf#page=17">[pdf]</a> <details markdown = "0"><summary markdown="0">[bib]</summary>
    <pre>@InProceedings{BeniamineBonamiMcDonough2017,
    author    = {Beniamine, Sacha and Bonami, Olivier and McDonough, Joyce},
    title     = {When segmentation helps.
                Implicative structure and
                morph boundaries in the Navajo verb},
    booktitle = {First International Symposium on Morphology (ISMo)},
    year      = {2017},
    pages     = {11--15},
    address   = {Lille, France},
    month     = {December},
    url       = {https://hal.inria.fr/halshs-01955118},
    }</pre>
    </details>
    <blockquote>
     Recent work in Word and Paradigm morphology argues that the implicative structure of paradigms is expressed in terms of relations between surface words, and that studying the structure of paradigms in terms of sub-word units is misleading if not outright impossible (Ackerman et al, 2009; Blevins, 2006, 2016; Bonami & Beniamine, 2016). The argument typically rests on the observation that a word can only be segmented in the context of its paradigmatic alternatives, and that different aspects of the paradigm lead to different segmentations for the same word.This line of argumentation amounts to a claim about the empirical properties of some inflection systems. It is thus entirely possible that systems differ in this respect. In this presentation we show that there are systems where a uniform segmentation is possible and helpful to addressing implicative structure. Interestingly though, the segments that are identified lack the properties of classical morphemes.
    </blockquote>
    </li>
  <li>Sacha Beniamine (2017). <b>“Un algorithme universel pour l'abstraction automatique d'alternances morphophonologiques”</b> . In: <em>Actes de Traitement Automatique des Langues Naturelles (TALN)</em> 2017. Vol. 2. Orléans, France, pp. 77–85. <a href="https://hal.inria.fr/hal-01615899/document">[pdf]</a> <details markdown = "0">
        <summary markdown="0">[bib]</summary>
        <pre>@InProceedings{Beniamine2017,
    author    = {Beniamine, Sacha},
    title     = {Un algorithme universel pour l'abstraction automatique
                d'alternances morphophonologiques},
    booktitle = {24e Conférence sur le Traitement
                Automatique des Langues Naturelles (TALN)},
    year      = {2017},
    volume    = {2},
    pages     = {77--85},
    address   = {Orléans, France},
    url       = {https://hal.inria.fr/hal-01615899},  
    PDF       = {https://hal.inria.fr/hal-01615899/file/tipapatternspaper.pdf},
        }</pre>
    </details>
    <blockquote>
        We present an implemented algorithm for the inference of morphophonological alternation patterns between word-forms. It is universal in that it leads to comparable classifications across languages without expectations on the shape of the alternations it searches for. Alternation patterns are anecessary first step for the quantitative study of morphology in the Word and Paradigm framework.
    </blockquote>
  </li>
  <li>Sacha Beniamine, Olivier Bonami, and Benoı̂t Sagot (2017). <b>“Inferring Inflection Classes with Description Length”</b> . In: <em>Journal of Language Modelling</em> 5.3, pp. 465–525. DOI: 10.15398/jlm.v5i3.184 <a href="https://hal.inria.fr/hal-01718879/document">[pdf]</a> <details markdown = "0"><summary markdown="0">[bib]</summary>
        <pre>@Article{BeniamineBonamiSagot2017,
    author   = {Beniamine, Sacha and Bonami, Olivier and Sagot, Beno{\^\i}t},
    title    = {Inferring Inflection Classes with Description Length},
    journal  = {Journal of Language Modelling},
    publisher = {Institute of Computer Science, Polish Academy of Sciences, Poland},
    year     = {2017},
    volume   = {5},
    number   = {3},
    month = Feb,
    pages    = {465--525},
    doi      = {10.15398/jlm.v5i3.184},
    pdf = {https://hal.inria.fr/hal-01718879/file/184-1460-1-PB.pdf},
    url = {https://hal.inria.fr/hal-01718879},
        }</pre>
    </details>
    <blockquote>
        We discuss the notion of an inflection class system, a traditional ingredient of the description of inflection systems of nontrivial complexity. We distinguish systems of microclasses, which partition a set of lexemes in classes with identical behavior, and systems of macroclasses,which group lexemes that are similar enough in a few larger classes. On the basis of the intuition that macroclasses should contribute to a concise description of the system, we propose one algorithmic method for inferring macroclasses from raw inflectional paradigms, based on minimisation of the description length of the system under a givenstrategy of identifying morphological alternations in paradigms. We then exhibit classifications produced by our implementation on French and European Portuguese conjugation data and argue that they constitute an appropriate systematisation of traditional classifications. To arrive at such a convincing systematisation, it was crucial for us to use a local approach to inflection class similarity (based on pairwise comparisons of paradigm cells) rather than a global approach (based on the simultaneous comparison of all cells). We conclude that it is indeed possible to infer inflectional macroclasses objectively.
    </blockquote>
    </li>

  <li>Olivier Bonami and S. Beniamine (2016). <b>“Joint predictiveness in inflectional paradigms”</b>. In: <em>Word Structure</em> 9.2, pp. 156–182. DOI: 10.3366/word.2016.0092  <a href="https://www.euppublishing.com/doi/pdfplus/10.3366/word.2016.0092">[on journal homepage]</a> <a href="http://www.llf.cnrs.fr/sites/llf.cnrs.fr/files/biblio/ws-jointprediction.pdf">[pdf]</a> <details markdown = "0"><summary markdown="0">[bib]</summary><em> Please cite my first name as "S." in this paper.</em>
        <pre>@Article{BonamiBeniamine2016,
    author   = {Bonami, Olivier and Beniamine, S.},
    title    = {Joint predictiveness in inflectional paradigms},
    journal  = {Word Structure},
    year     = {2016},
    volume   = {9},
    number   = {2},
    pages    = {156--182},
    doi      = {10.3366/word.2016.0092},
    url      = {http://dx.doi.org/10.3366/word.2016.0092},
    keywords = {checked},
    editor   = {Farrell Ackerman and Malouf, Robert}
        }
        </pre>
    </details>
<blockquote>This paper contributes to addressing the Paradigm Cell Filling Problem (PCFP) in inflectional paradigms, as defined by Ackerman et al. (2009). We define a method for extending the use of conditional entropy to address the PCFP to prediction based on multiple paradigm cells. We apply this method to French and European Portugese and show that, on average, knowledge of multiple paradigm cells is dramatically more predictive than knowledge of a single cell. Moreover, this new entropy measure proves useful in studying principal parts systems, which correspond to sets of predictors yielding a null entropy. Using a graded measure allows us to highlight the relevance of non-categorical or “good enough” principal parts systems.</blockquote></li>

  <li>Olivier Bonami and S. Beniamine (2015). <b>“Implicative structure and joint predictiveness”</b>. In: <em>Proceedings of the NetWordS Final Conference on Word Knowledge and Word Usage: Representations and Processes in the Mental Lexicon.</em> Ed. by Vito Pirelli, Claudia Marzi, and Marcello Ferro. Pisa, Italy. <a href="http://ceur-ws.org/Vol-1347/">[url]</a> <details markdown = "0"><summary markdown="0">[bib]</summary><em> Please cite my first name as "S." in this paper.</em>
        <pre>@InProceedings{BonamiBeniamine2015,
    author    = {Bonami, Olivier and S. Beniamine},
    title     = {Implicative structure and joint predictiveness},
    booktitle = {Proceedings of the NetWordS Final Conference
                on Word Knowledge and Word Usage:
                Representations and Processes in the Mental Lexicon},
    year      = {2015},
    editor    = {Vito Pirelli and Claudia Marzi and Marcello Ferro},
    address   = {Pisa, Italy},
    url       = {http://ceur-ws.org/Vol-1347/},
        }</pre>
    </details></li>
</ul>

## Datasets

<ul class="datasets">
<li>Sacha Beniamine and Dunstan Brown. (2019). Inflected lexicon of Russian Nouns in IPA notation  [Data set]. <a href="https://doi.org/10.5281/zenodo.3428591"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.3428591.svg" alt="DOI"></a> <a href="https://pure.york.ac.uk/portal/en/datasets/russian-nouns-ipa-notation-with-stress(04f2d69c-72ac-4c46-aa71-80c50d245c1e).html">[York Research Database]</a><a href="https://gitlab.com/sbeniamine/russiannounlexicon">[gitlab]</a> <details markdown = "0"><summary markdown="0">[bib]</summary>
        <pre>@Misc{BeniamineBrown2019,
  author       = {Sacha Beniamine and Dunstan Brown},
  title        = {Inflected lexicon of Russian Nouns in IPA notation},
  howpublished = {Online repository},
  year         = {2019},
  doi          = {10.5281/zenodo.3428591},
  url          = {https://gitlab.com/sbeniamine/russiannounlexicon},
        }
        </pre>
    </details><blockquote>This inflected lexicon of Russian Nouns is based on data generated by a DATR fragment for the nominal system of Russian (Dunstan Brown et al, 2011), which was used in Brown and Hippisley (2012). The files were automatically transcribed to an IPA-based notation by Sacha Beniamine (2018), following rules provided by Dunstan Brown. We also corrected a few errors in the original data found manually. We thank Sasha krasovitsky for providing comments on the phonological feature definitions.
</blockquote></li>
<li>Sacha Beniamine, Martin Maiden and Erich Round. (2019) The Romance Verbal Inflection Dataset V.2 [Data Set]. <a href="https://doi.org/10.5281/zenodo.3552367"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.3552367.svg" alt="DOI"></a><a href="https://gitlab.com/sbeniamine/Romance_Verbal_Inflection_Dataset/">[gitlab]</a><details markdown = "0"><summary markdown="0">[bib]</summary>
        <pre>@Misc{BeniamineMaidenRound2019,
  author       = {Sacha Beniamine and Martin Maiden and Erich Round},
  title        = {Romance Verbal Inflection Dataset 2.0},
  howpublished = {Online repository},
  year         = {2019},
  doi          = {10.5281/zenodo.3552367},
  url          = {https://gitlab.com/sbeniamine/Romance_Verbal_Inflection_Dataset},
        }</pre></details><blockquote>The Romance Verbal Inflection Dataset 2.0 is a multilingual lexicon of Romance inflection covering 73 varieties. It provides verbal paradigm forms in broad IPA phonemic notation. To facilitate historical comparisons, it includes Latin paradigms. It constituted a revised and machine readable version of the Oxford Online Database of Romance Verb Morphology. It is released under a GPLv3 license in CLDF format.</blockquote>
    </li>
</ul>

## Tools

* <img src="qumin.png" alt="Qumin" style="vertical-align:sub;" width="80px"> (*Qu*antitative *M*odelling of *In*flection) is a set of scripts written during my PhD to explore the structure of inflection class systems. [[doc]](http://www.llf.cnrs.fr/partage/qumin/) [[code]](https://github.com/XachaB/Qumin)
* [pdcldf](https://pypi.org/project/pdcldf/), a very thin wrapper on [pycldf](https://pypi.org/project/pycldf/) to write pandas DataFrames as [CLDF](https://cldf.clld.org/) datasets. It implements some boilerplate to automatically add components, tables and columns, and deduce as much metadata as possible from pandas DataFrames rather than specify every column.
* [IPA Keyboard](https://github.com/XachaB/IPAKeyboard) is a keyboard layout for Onboard Keyboard, allowing for easily typing International Phonetic Alphabet symbols in utf-8 on linux.
