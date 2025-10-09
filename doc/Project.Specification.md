% Project Specification
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

# Overview

This seminar is centred around your own personal project. Over the course of the term, you will select a short handwritten text or excerpt of circa 300 words, medieval or early Modern at the latest, transcribe and encode it in TEI XML, write a brief scholarly introduction, mark up your text with a range of metadata, style it in CSS, access the document tree using Python, generate a basic statistical profile of the text, and document your methods in a Jupyter notebook. The present document specifies the requirements and should be read in conjunction with four further documents: the course syllabus, which specifies what part of the work is due when; the [Project Suggestions](https://github.com/langeslag/words-methods/blob/main/doc/Project.Suggestions.pdf); the [Presentation Specification](https://github.com/langeslag/words-methods/blob/main/doc/Presentation.Specification.pdf); and the [Resources](https://github.com/langeslag/words-methods/blob/main/doc/Resources.pdf) document.

# Scholarly Introduction

As part of your project, you will write a brief scholarly introduction of 300 words or more, encoded in the relevant parts of the TEI header. It should at least have a palaeographical component describing the text's transmission (the surviving manuscript witnesses, their date and origin, your choice of manuscript) and especially that of the chosen witness. The introduction should address at least one further scholarly question of your choosing, such as authorship, date of composition, dialect, sources, metrics, or vocabulary; this information may be gleaned from existing scholarship (which should be duly cited; see [TEI Guidelines § 3.12, "Bibliographic Citations and References"](https://tei-c.org/release/doc/tei-p5-doc/en/html/CO.html#COBI)) along with your own research. The introduction is best written after you have gained a familiarity with the text and its scholarship, and in close conjunction with your class presentation.

# Encoding Specification

## Mandatory Markup

Your text or excerpt should be encoded following the [TEI P5 standard](https://tei-c.org/guidelines/p5/) on the basis of the template supplied in the course repository, with at least the following features:

- A codicological account of your manuscript in [the TEI header](https://tei-c.org/release/doc/tei-p5-doc/en/html/HD.html) (see [TEI P5 ch. 11, "Manuscript Description"](https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html));
- Such basic units of markup as `<l>`{.xml} (for verse) or `<p>`{.xml} (for prose; see [TEI P5 ch. 3, "Elements Available in All TEI Documents"](https://tei-c.org/release/doc/tei-p5-doc/en/html/CO.html));
- Abbreviations, using at least `<ex>`{.xml} to indicate supplied expansions, or `<choice>`{.xml} nodes with children `<abbr>`{.xml} and `<expan>`{.xml}, and/or `<am>`{.xml} and `<ex>`{.xml}, where required;
- Scribal interventions and your own editorial emendations (`<add>`{.xml}, `<del>`{.xml}, `<sic>`{.xml}, `<corr>`{.xml}, wrapped in `<choice>`{.xml} as required, alongside `<surplus>`{.xml} and `<supplied>`{.xml} as needed; likewise documented in [ch. 3 of the TEI Guidelines](https://tei-c.org/release/doc/tei-p5-doc/en/html/CO.html)).

## Advanced Markup

You are expected to mark up your text with at least two of the following three additional types of metadata, or others like it:

- lemmatization (`<w>`{.xml} with `@lemma`; see [TEI P5 ch. 18, "Simple Analytic Mechanisms"](https://tei-c.org/release/doc/tei-p5-doc/en/html/AI.html)):
- part of speech (`<w>`{.xml} with `@pos`; likewise documented in [ch. 18 of the TEI Guidelines](https://tei-c.org/release/doc/tei-p5-doc/en/html/ai.html));
- metre (`<l>`{.xml} with `@met`, and/or `<seg>`{.xml} with `@met` for halflines; see [TEI P5 ch. 6, "Verse"](https://tei-c.org/release/doc/tei-p5-doc/en/html/index.html)).

The format of your lemma and POS references is up to you; we will discuss some of the options in class.

## Additional Markup

You are encouraged, but not required, to encode such further types of information as

- named entities (`<persName>`{.xml}, `<placeName>`{.xml}, `<name>`{.xml});
- geolocation (`<geo>`{.xml}).

# Styling

Your project should include a personalized adaptation of the CSS stylesheet template supplied in the course repository, and it should render appropriately.

# Evaluation

Your project should include Jupyter notebooks demonstrating at least the following features, each amply documented in a markdown cell and/or code comments:

- Retrieval of your XML text nodes into lists of tokens, preserving such structures as verse lines or paragraphs
- A metadata structure for such features as part of speech, lemmata, and/or metrical data
- Some basic statistics on tokens and metadata (token count, term-to-token ratio, metrical trend lines)
- At least one graph (e.g. frequencies of different parts of speech)
