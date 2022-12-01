---
documentclass: article
mainfont: "fbb"
fontsize: 11pt
geometry: margin=1.5in
header-includes:
- \usepackage{fancyhdr, array, ifthen}
- \newcommand{\sectionbreak}{\clearpage}
- \pagestyle{fancy}
- \fancyhf{}
- \renewcommand{\headrulewidth}{0pt}
- | 
    \rhead{
        \ifthenelse{\value{page}=1}
        {\textbf{Department of English and Comparative Literature} | Summer 2023}
        {}
    }
- \fancyfoot[CO, CE] {\thepage}
---

# Introduction to Language and Computation
w/ Prof. Dennis Yi Tenen

## Course Description

How would you teach a computer to read a novel? In answering this question over the course of a
summer semester, we will have to get down to the pixel---and then work our way up to larger
units comprising language: words, sentences, paragraphs, stories, and story collections. Along
the way, students will be introduced to basic concepts in linguistics and formal analysis, by
using simple computational tools, available on any computer. These building blocks will help us
become better close---closest possible---readers of texts, but also to perceive patterns and
structures at scale, visible across long-distances, in archival time and space. No prior
experience is necessary to participate: the only course requirement is interest in language,
history, and technology.

## Course Structure

3 hour sessions, 2 times a week, for 6 weeks.

We will generally spend the first section of the week on discussing the reading and the second
session on workshops and excesses, in preparation for homework.

## Provisional Schedule & Reading List

### Week 1: Letter

What is a letter? The history of alphabets. Glyphs and hieroglyphs. Telegraph codes. Character
encoding. From memory to pixel.

- Selections form *An Essay Towards a Real Character, and a Philosophical Language* (1668) by
  John Wilkins.
- Selections from *Plain Text* (2017) from Dennis Yi Tenen.

Worksheet 1

### Week 2: Word

Word boundaries. Parts of speech. Types and tokens. Spelling and misspelling. Counting words.

- Selections form *How to Read a Word* (2010) by Elizabeth Knowles.
- Selections from *Speech and Language Processing* (2008) by Dan Jurafsky and James Martin.
- Selections from *Foundations of Statistical Natural Language Processing* (1999) by
  Christopher D. Manning and Hinrich Schütze.
- "Boris Yarkho's works on literary theory" by Mikhail Gasparov in *Studia Metrica et Poetica*
  2016.2: 130–15.

Worksheet 2

### Week 3: Sentence

Syntax. Sentence clause structure. Semantic roles. Punctuation.

- Selections from *Syntactic Structures* (1957) by Noam Chomsky.
- Selections from *Studies in Lexical Relations* (1965) by Jeffrey Gruber.
- "Types of Lexical Information" in *Semantics: An Interdisciplinary Reader in Philosophy,
  Linguistics and Psychology* (1971) by Charles Fillmore.
- Selections from *Pause and Effect: An Introduction to the History of Punctuation in the West*
(1992) by M.B. Parkes.

Worksheet 3

### Week 4: Paragraph

Patterns and arrangements. Composition. Style guides.

- Selections from *The History of the English Paragraph* (1894) by Lewis Herbert.
- Selections from [*English Composition and Rhetoric*][40] (1866) by Alexander Bain.
- "The Stadium of Discourse" by Paul Rodgers in CCC 18 (1967): 148-51.
- Selections from *Strategies of Discourse Comprehension* by Teun van Dijk and Walter Kintsch.

[40]: https://archive.org/details/historyofenglish00lewirich

Worksheet 4

### Week 5: Story

Visualizing stories. Context persistence.

Worksheet 5

### Week 6: Collection, Archive

Historical and institutional context. Sample bias. Corpus analysis.

Worksheet 6

## Course Requirements & Grading

- 25%     Class and online participation
- 25%     Weekly worksheets
- 25%     Final exam
- 25%     Final paper / project

## University Policies

When in doubt, cite! Plagiarism is insulting to your fellow students, your instructors, and to
the research community at large. It wastes my time and yours, and is, ultimately, not worth the
risk. Consult Columbia’s guidelines at <http://www.college.columbia.edu/academics/integrity> or
ask me for help early in the writing process. We will discuss the ethics of code reuse in a
separate session.
