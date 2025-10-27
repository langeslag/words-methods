% Project Suggestions
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

# Project Outline

For your project, you will choose a medieval (e.g. Old English, Middle English, Latin, or Old Norse) or else an early Modern (e.g. English) manuscript passage of approximately 300 words, transcribe it, mark it up with lexical information and other metadata and provide it with a scholarly introduction, and then subject it to styling, processing, and mechanical evaluation. It will help to have some basic understanding of the language you will be working with, as will the ability to read the script used! So apart from choosing a genre and text that interests you, go for a language and script that you don't find overly intimidating. If you lack training in medieval English but have a basic background in Latin, you'll probably want to undertake a project involving that language; if you have none of the above, either take the language challenge in stride or else find an early modern object of study. Poetry is of particular interest because it calls for line and metrical markup, but prose is acceptable particularly if you can think of additional data to encode. For instance, consider the challenges posed by [the encoding of runic characters and their transliteration](https://www.menota.org/HB4_ch18.xml), or of [maps](https://digital.bodleian.ox.ac.uk/objects/acd9492e-25fa-4286-9fe6-e0cf2fc28106/surfaces/27e0b7cb-ae81-4bdc-a127-d3815147690e/), or the interlinking possibilities offered by glosses or other multilingual texts. However, verse projects offer even more worthwhile markup challenges: think of [musical notation](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-musicNotation.html) (see also [MEI](https://music-encoding.org/guidelines/v3/content/neumes.html)) and solutions to the syntactical and circumlocutory challenges posed by skaldic poetry.

# Project Suggestions

## Riddles (Old English, Latin)

The riddles of the [Exeter Book](https://theexeterbook.exeter.ac.uk/) (fols 101^r^--115^r^, 122^v^--130^v^) are Old English poems, often adapted from Latin models, ranging from a few lines to dozens. As they are in verse, they are eligible for metrical markup. You can select a few riddles on a particular theme, or edit an Old English riddle along with its Latin model. Hunt down Andy Orchard's two-volume edition in the [Dumbarton Oaks Medieval Library (DOML)](https://domedieval.org/volumes/old-english/) series (try [interlibrary loan](https://kxp.k10plus.de/DB=2.1/LNG=DU/)) for the most detailed study to date, but maybe start with Megan Cavell's [Riddle Ages](https://theriddleages.bham.ac.uk/) website. For your edition, also keep in mind Ruby Ku's [typeface](https://github.com/rubywku/exeterbookhand) emulating the Exeter Book's characteristic script!

If Old English is not your thing, look for the Latin _Aenigmata_ of Symphosius, Aldhelm, Boniface, Bede, or Alcuin. These too are edited, translated, and described in Orchard's study, and manuscripts may easily be found on [e-codices](https://e-codices.ch/) with the query "aenigmata", or in the [British Library](https://www.bl.uk/collection/digitised-manuscripts-archives) as "aenigmata" or "riddles".

## Charms (Old English)

The Old English charms are metrical instructions alleged to effect healing, fertility, and the like. [The edition by Godfrid Storms](https://opac.sub.uni-goettingen.de/DB=1/XMLPRS=N/PPN?PPN=065565541) remains the easiest way into this material, but a series of charms have more recently been edited and tranlated for [DOML](https://domedieval.org/volumes/old-english/)'s _Wisdom and Lyric_ volume. Of the manuscripts currently online, [British Library, MS Royal D 12 xvii](https://iiif.bl.uk/uv/#?manifest=https://bl.digirati.io/iiif/ark:/81055/vdc_100101103280.0x000001) has the largest number of these.

## Medical and Alchemical Recipes (Old English, Middle English, Latin)

The Old English medical recipes are prose texts, contained in some of the same manuscripts as the verse charms, so here too you may want to take your pick from [British Library, MS Royal D 12 xvii](https://iiif.bl.uk/uv/#?manifest=https://bl.digirati.io/iiif/ark:/81055/vdc_100101103280.0x000001). The main collections are known as _Bald’s Leechbook_, _Leechbook III_, the _Herbarium_, _Peri didaxeon_, _Medicina de quadrupedibus_, and _Lacnunga_. Several of these have recently been edited and translated for the [DOML](https://domedieval.org/volumes/old-english/) series, and the rest are forthcoming. But you can also use Pettit's edition from the library.

You can find five editions of Middle English medical texts in the [Corpus of Middle English Prose and Verse (CME)](https://quod.lib.umich.edu/c/cme/) (see under Browse &gt; Anonymous &gt; Medicine). The editions should tell you what manuscripts they edit.

[This Cambridge Digital Library collection](https://cudl.lib.cam.ac.uk/collections/medievalmedicalrecipes) links to dozens (!) of medical and alchemical manuscripts in Latin and English, so if you're interested in this field but not Old English, this is a great place to go looking for a project text.

Alchemy was introduced in Europe from the Arabic world in the twelfth century, so its manuscripts are exclusively high and late medieval, not Old English.

This genre tends to be prose, so if you choose it, you may want to think about encoding classification properties on a per-text and per-ingredient basis.

## Eddic and Skaldic Poetry (Old Norse)

[The Skaldic Project](https://skaldic.org/) is well on its way to editing all Old Norse poetry anew, and they provide at least the text of poems not yet re-edited. For the many poems newly edited, the website gives text, translation, and and introduction, and the website also has indices of kennings and heiti, among other resources. If you can figure out how the skaldic stanzas work syntactically, it may be worth encoding this information in some form to help readers make sense of the text as they hover it with their mouse or touch interface, as well as for mechanical evaluation.

## Romance (Middle English, Old French, Old Norse)

While the romances are too long for your project, you could select a brief episode. The [Database of Middle English Romance](https://www.middleenglishromance.org.uk/) summarizes plots and lists manuscripts and editions of Middle English romances. Marianne E. Kalinke has translated and described the Old Norse romances, and edited a few, across several publications. You can find OCR text of earlier editions at <https://heimskringla.no>.

## Lyrics and other Poetry (Old English, Middle English, Latin)

Also contained in the [Exeter Book](https://theexeterbook.exeter.ac.uk/) are a range of lyrics (traditionally referred to as "elegies") and other poems told from a first-person perspective that fit comparatively well with our length constraint. Really any text or excerpt of appropriate length from the Exeter Book will do, or any passage from the long poems in [MS Junius 11](https://digital.bodleian.ox.ac.uk/objects/d5e3a9fc-abaa-4649-ae48-be207ce8da15/), for which latter you may additionally have occasion to include one of the manuscript's illustrations.

For Middle English lyrics, you'll first want to ascertain which manuscripts are available online: for instance, MS Digby 102 is not, so there is no point in looking at Thomas Duncan's otherwise very accessible edition of the Digby lyrics. Instead, consult his _Medieval English Lyrics: 1200--1400_ and verify for each text you're interested in whether manuscript images are readily available; or consult Julia Boffey's “Middle English Lyrics and Manuscripts.” There is no shortage of Middle English nature lyrics or religious poems, but again many of the manuscripts are not available online.

For Latin, you could choose one or more of the [Cambridge Songs](https://cudl.lib.cam.ac.uk/view/MS-GG-00005-00035/1). If you're interested in musical notation and welcome the additional challenge, you could choose a manuscript with neumes from [The Digital Image Archive of Medieval Music (DIAMM)](https://www.diamm.ac.uk/), e.g. the [Winchester Troper](https://parker.stanford.edu/parker/catalog/yp193mg4537), and puzzle over how to encode these.

## Runes and Inscriptions (Old English, Old Norse, Latin)

If you choose to work with runes, your project may use fewer total words, but you will need to teach yourself the conventions of runic transcription and transliteration, and possibly the encoding of OpenType features to be able to display variant forms not directly available through Unicode code points. Ray Page's _Introduction to English Runes_ and Michael Barnes's _Runes: A Handbook_ may serve to get you started in the field, while the [chapter on runes](https://www.menota.org/HB4_ch18.xml) in the _Menota Handbook_ is an excellent primer on the technological workflow.

A digital edition of the Franks Casket (or Auzon Casket) offers a fantastic opportunity to bring together Old English and Latin, runic script and Roman, text and image. The British Museum has good [images](https://www.britishmuseum.org/collection/object/H_1867-0120-1) of all five panels; the text has recently been edited by Gaby Waxenberger for the volume [_Old English Runes: Interdisciplinary Perspectives on Approaches and Methodologies_](https://opac.sub.uni-goettingen.de/DB=1/XMLPRS=N/PPN?PPN=1809345979). Please be advised, however, that not all texts on the object have been satisfactorily explained, and any one scholar's reading you follow is more likely than not to contain misinterpretations.

An edition of the Ruthwell Cross represents a similarly ambitious project. Kerstin Majewski has recently published a [study and edition](https://opac.sub.uni-goettingen.de/DB=1/XMLPRS=N/PPN?PPN=1819124258) of this object and its inscriptions.

There is no shortage of runic inscriptions in Scandinavia; if you can cobble together a sufficiently sized corpus of some coherence, feel free to make this your project. You may want to start at [Runor](https://app.raa.se/open/runor/), which (often) has images, full transcriptions, and translations, as well as geolocations, dates, and other metadata.

Latin inscriptions can, of course, be found more widely; the challenge here is rather to find a sufficiently sized corpus that is also of sufficient interest to qualify for an edition. My main criterion for the approval of such a project is sufficient age: let's not edit eighteenth-century commemorative inscriptions if there's Carolingian inscriptions to be had. I'm happy to go the other direction and accept a corpus of Roman graffiti from Pompeii or Herculaneum (see the [Ancient Graffiti Project](https://ancientgraffiti.org/)); but surely there are also worthwhile inscriptions in Germany, which you could go and photograph yourself.

## Wisdom Literature (Old English, Middle English, Old Norse, Latin)

Prominent examples of Old English wisdom literature are the two sets of metrical _Maxims_, contained in the [Exeter Book](https://theexeterbook.exeter.ac.uk/) and in MS Cotton Tiberius B. i (currently not available online), as well as a range of prose and verse dialogues, notably the verse _Solomon and Saturn I_ and _II_, in [Cambridge, Corpus Christi College MS 422](https://parker.stanford.edu/parker/catalog/fr610kh2998) (pp. 1--6, 13--26) and the two prose treatments of the same material in the same manuscript (pp. 6--12) and in [MS Cotton Vitellius A. xv](https://ebeowulf.uky.edu/ebeo4.0/CD/main.html) (fols 86^v^--93^v^). Daniel Anlezark has studied and edited the _Solomon and Saturn_ material, while Bjork's _Wisdom and Lyric_ volume of [DOML](https://domedieval.org/volumes/old-english/) prints text and translation of _Maxims II_ as well as the two _Solomon and Saturn_ poems.

In Latin, you could look at the _Distichs of Cato_ material --- these are not actually Cato's work, but an amorphous collection of maxims transmitted in his name. An early edition and translation is that by [Chase](https://archive.org/details/distichsofcatofa00chasrich). For manuscripts, run a search for "disticha catonis" on [e-codices](https://e-codices.ch/) or in any other repository. Middle English Cato material has been edited by [Max Förster](https://archive.org/details/englische-studien_1906_36/page/n9/mode/2up), but is currently not well represented in online fascimiles, so I recommend against pursuing that particular avenue. Cato material is also available in Old English (prose), under the conventional title _Dicts of Cato_, e.g. in [MS Cotton Julius A ii](https://iiif.bl.uk/uv/#?manifest=https://bl.digirati.io/iiif/ark:/81055/vdc_100060432971.0x000001) (fols 141^r^--144^v^). You can also look under "Cato", or under "Proverbs", in the index to Ker's _Catalogue of Manuscripts Containing Anglo-Saxon_: there are many brief entries, often with Latin and Old English side by side.

Old Norse wisdom literature takes many forms: there is the _Konungs skuggsjá_ passing on the knowledge a prospective ruler should have, as well as the maxims and wisdom exchanges in the Eddic poetry (_Hávamál_, _Vafþrúðnismál_, etc.). Another approach, involving transcriptions from multiple carriers, could be to rely on [_ONP_'s index of proverbs](https://onp.ku.dk/onp/onp.php?q35), or Richard Harris's [Concordance to the Proverbs and Proverbial Materials of the Old Icelandic Sagas](http://www.usask.ca/english/icelanders), select an appropriate number of these using some criterion, and transcribe them from across a range of manuscripts. This involves a bit more organization.

## Early Modern Manuscripts

If you find medieval languages too intimidating, you may choose an early Modern project (i.e. predating ca. 1700), provided your object of study is handwritten. For early Modern English, consult the [Catalogue of English Literary Manuscripts 1450–1700](https://celm.folger.edu) for ideas.

\newpage

# Inspiration

The following resources may help you find a manuscript passage for your project:

- N. R. Ker, [_Catalogue of Manuscripts Containing Anglo-Saxon_](https://opac.sub.uni-goettingen.de/DB=1/XMLPRS=N/PPN?PPN=110815645)

  (Near-complete index of Old English manuscripts and fragments.)

- [Resources for Old English Prose](https://roep.web.ox.ac.uk/)

  (Overviews of Old English prose works.)

- [Corpus of Middle English Prose and Verse](https://quod.lib.umich.edu/c/cme/)

  (HTML conversions of print editions.)

- [Database of Middle English Romance](https://www.middleenglishromance.org.uk/)

  (Summarizes plots and lists manuscripts and editions.)

- [The Electronic _Beowulf_](https://ebeowulf.uky.edu/ebeo4.0/CD/main.html)

  (Text, facsimile, grammar, metre, glossary, translation.)

- [CLASP: A Consolidated Library of Anglo-Saxon Poetry](https://clasp.ell.ox.ac.uk/)

  (Text and metre of Old English and [Anglo-]Latin poetry.)

- [ECHOE: The Electronic Corpus of Anonymous Homilies in Old English](https://echoe.uni-goettingen.de/)

  (Text, facsimile, sources, and filters for motifs, preaching occasions, and sources used.)

- [The Skaldic Project](https://skaldic.org/)

  (Texts with introduction, translation, commentary, glossary.)
