% Presentation Specification
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

# Requirement

- [B.Eng.611](https://flexnow2.uni-goettingen.de/modulbeschreibungen/120927.pdf) requires a ten-minute presentation;
- [B.DH.11](https://flexnow2.uni-goettingen.de/modulbeschreibungen/112871.pdf) and [SK.DH.04](https://flexnow2.uni-goettingen.de/modulbeschreibungen/85915.pdf) require a twenty-minute presentation, to be written up into a ten-page term paper.

# Rationale

Student presentations should always contribute something of interest to all attendees, yet they cannot all cover the same ground.

# Guidelines

The __B.Eng.611__ presentation should therefore foreground the text and carrier as cultural artefacts. Technical questions, such as what kinds of transcription challenges the performance poses and what metadata may be encoded, should be addressed briefly but not assume centre stage. Instead, students will want to explain e.g. the characteristics of the genre and the place of the chosen text in it, or what we can infer about the time and date of its composition and transmission. The audience should learn something, but also be entertained.

The __B.DH.11/SK.DH.04__ presentation should start with the same sort of cultural focus, but develop into a technical assessment of the place the text and its genre assume within the language corpus and what analytical potential they offer within the field of NLP. The writeup should accordingly treat the chosen text as a case study for what analytical work could be done if other texts like it were subjected to the same kind of encoding, and seek novel approaches if possible. In rare cases, where the text type is exceptionally well-attested or individual texts are sufficiently long, there may be potential for machine learning, but in most cases the potential will be statistical. For instance:

- Lexical clustering: patterns of diction may reveal differences in subject matter, style, and occasionally dialect or authorship.
- Poetic compounding: do poems differ in their creative choices in some quantifiable way?
- Metrical clustering: ditto.
- Token length: does your genre stand out in having unusually low or high average numbers of characters per word, to the extent that you can reliably classify documents by this metric?

As the examples suggest, the strongest B.DH.11/SK.DH.04 presentations and term papers will involve corpus research well beyond the document transcribed. To this end, some class time throughout the term will be devoted to the discussion of potential approaches and strategies, so DH students can pursue these research avenues alongside their project work.
