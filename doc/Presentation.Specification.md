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

Students of [B.Eng.611](https://flexnow2.uni-goettingen.de/modulbeschreibungen/120927.pdf) are required to give a ten-minute presentation. Students of DH/SK modules are not.

# Rationale

Student presentations should always help the presenters think about worthwhile approaches to their subject matter, but also contribute something of interest to all attendees, yet they cannot all cover the same ground.

# Guidelines

The presentation should therefore foreground the text and carrier as cultural artefacts, explaining e.g. the characteristics of the genre and the place of the chosen text in it, or what we can infer about the time and date of its composition and transmission. The audience should learn something, but also be entertained.

For full points, presentations should also include a brief speculative component in which the presenter discusses what questions they hope to answer by comparing the text with a larger corpus using quantitative methods after the winter break. For instance:

- Lexical outliers: Do you expect your text contains rare or unique words or word forms? Why?
- Echoes: Does your text contain any verses, phrases, or compounds that you expect are *not* unique to this composition, or that may be considered formulaic? How do you plan to test this hypothesis?
- Metrical profile: If your text is in verse form, what metrical variables (e.g. words per line, distribution of Sievers types, proportion of unstressed syllables) are testable against a larger corpus, and what do you expect to learn by conducting such an analysis?
- Dating: If your text has not been firmly dated, are there any tests we could run to give us an indication?
- Token length: Does your chosen genre stand out in having unusually low or high average numbers of characters per word, to the extent that you can reliably classify documents by this metric?

Thinking about these questions will help you and your audience come up with the most valuable metadata to encode and the most meaningful approaches to data evaluation for your portfolio.
