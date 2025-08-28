% Resources
% Medieval Words, Modern Methods
% revision of \today

---
mainfont: Junicode
header-includes: |
	  ```{=latex}
	  \usepackage{fullpage}
	  \usepackage[strict]{changepage}
      \newcommand{\hideFromPandoc}[1]{#1}
      \hideFromPandoc{
        \let\Begin\begin
        \let\End\end
	  \definecolor{burgundy}{HTML}{990000}
      }

	  ```
urlcolor: burgundy
---

# Manuscripts

## Old and Middle English

For Old English manuscripts, Ker's _Catalogue of Manuscripts Containing Anglo-Saxon_ describes the extant manuscripts and their contents. For slightly later, transitional manuscripts (1060--1220), the [EM1060](https://em1060.stanford.edu/) project has online descriptions. Online manuscript images are largely found in the following repositories (ideally with a range of metadata on the manuscript and its contents):

- [The Parker Library](https://parker.stanford.edu/): manuscripts in Cambridge, Corpus Christi College
- [The British Library](https://www.bl.uk/research/digitised-manuscripts/): not all of these are back online yet after a ransomware attack. Follow the links in the PDF.
- [The Bodleian Libraries](https://digital.bodleian.ox.ac.uk/): Oxford manuscripts.
- [The Cambridge Digital Library](https://cudl.lib.cam.ac.uk/) pulls together manuscripts and other text carriers from across the Cambridge collections; use its search function.
- [ECHOE](https://echoe.uni-goettingen.de/): some of the Oxford manuscripts not yet available through the Bodleian may be accessed here. Just select a homily from the relevant manuscript, maximize the facsimile window, then select the desired folio.

## Latin

- [e-codices](https://e-codices.ch/): though these are Swiss holdings only, they are plenty. Some High German here as well.
- [BnF Gallica](https://gallica.bnf.fr/): holdings of the _Bibliothèque nationale de France_.
- The [Herzog August Bibliothek](https://www.hab.de/handschriften/) in Wolfenbüttel has the largest manuscript collection in our immediate vicinity.
- The [SUB](https://www.sub.uni-goettingen.de)'s [Digitalisierungszentrum](https://gdz.sub.uni-goettingen.de/) has a collection of [medieval manuscripts](https://gdz.sub.uni-goettingen.de/collection/DDB_NEUSTART_KULTUR) and another of [fragments](https://gdz.sub.uni-goettingen.de/collection/mittelalterliche_fragmente).

## Old Norse

- [handrit.is](http://handrit.is)

## Modern English

- [Catalogue of English Literary Manuscripts 1450–1700](https://celm.folger.edu)

# Dictionaries

## Old English

- [_DOE A--Le_](https://doe.artsci.utoronto.ca/) (access via EduVPN) is the leading dictionary, but incomplete and for some reason barely functional when accessed through our library. Unless you're an expert, you'll want to use their "attested spelling" search field.
- [Bosworth and Toller](https://bosworthtoller.com/) is outdated, but it's complete and freely accessible online. Just be sure to learn (1) the difference between the multiple volumes (the 1898 main dictionary, the 1921 supplement, and the 1972 addenda and corrigenda not in the online dictionary) and (2) how to cite the original print publications as well as the website.

## Middle English

- [_Middle English Dictionary_](https://quod.lib.umich.edu/m/middle-english-dictionary/dictionary)

## Latin

- [Logeion](http://logeion.uchicago.edu/) incorporates multiple dictionaries, including the recent _Dictionary of Medieval Latin from British Sources (DMLBS)_. Be advised: unlike most Latin dictionaries, _DMLBS_ lists verbs under the present infinitive, not the first-person singular indicative form, so you'll want to adapt your query to the dictionary you wish to consult.

## Old Norse

- [_The Dictionary of Old Norse Prose (ONP)_](https://onp.ku.dk/): just be aware this dictionary is (1) incomplete, and (2) based on a selection of prose sources, not the complete corpus of Old Norse prose. But if your Old Norse is good enough, you can figure out the sense of words not yet described by consulting the citation slips.
- Fritzner: this is the best complete dictionary of Old Norse, but it is in Norwegian. Simply use the _ONP_ search field and click through to Fritzner.
- Cleasby--Vigfusson: this is the dictionary most used by those who cannot read Scandinavian. It's not perfect. You can access it through _ONP_ or at <https://old-norse.net>.

# Verse and Metre

## Old English

If you choose an Old English verse text, [CLASP](https://clasp.ell.ox.ac.uk/) may help you with the line division and the metre. For _Beowulf_, [_e-Beowulf_](https://ebeowulf.uky.edu/ebeo4.0/CD/main.html) has you covered.

# Typefaces

## General

To be able to display medieval punctuation, you will need a [MUFI](https://mufi.info/)-compliant typeface, which largely limits you to [Junicode](https://github.com/psb1558/Junicode-font).

## Old English

However, if you are working with the Exeter Book or other Old English content, you may additionally want to experiment with the [Exeter Book Hand](https://exeterbookhand.com/).
