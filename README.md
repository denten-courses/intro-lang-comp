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
        {\textbf{Sungkyunkwan University} | Summer 2025}
        {}
    }
- \fancyfoot[CO, CE] {\thepage}
---

# Language and Computation
w/ Prof. Dennis Yi Tenen

## Course Description

How would you teach a computer to read a novel? In answering this question over the course of a
summer semester, we will have to get down to the letter---and then work our way up to larger
units comprising written language: words, sentences, paragraphs, stories, and story
collections. Along the way, students will be introduced to basic concepts in linguistics and
formal literary analysis, by using simple computational tools. These building blocks will help
us become better close---closest possible---readers of texts, but also to perceive patterns and
structures at scale, visible across long-distances, in archival time and space. No prior
experience is necessary to participate: the only course requirement is interest in language,
history, and technology.

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

### Week 5: Story, Narrative, Discourse

Visualizing stories. Myth, plot, situation. Genre. Structure and texture. Context persistence.

-  Selections from *Speech Genres and Other Late Essays* by Michail Bakhtin.
- "Stalking a Generative Poetics." by Schauber, Ellen, and Ellen Spolsky in *New Literary
  History* 12.3 (1981): 397-413.
- "Paradigm Shift in Plot Models: An Outline of the History of Narratology" by Ruth Ronen in
  *Poetics Today* 1990 11(4):817–842.

Worksheet 5

### Week 6: Collection, Archive

Historical and institutional context. Description vs. prescription. Sample bias. Corpus
analysis.

- "Towards a Description of English Usage" by Randolph  Quirk in the *Transactions of the
  Philological Society* (November 1960).
-  "A Vector Space Model for Automatic Indexing" by Gerard Salton and others in *Communications
   of the Association for Computing Machinery*  (1975) 18.11:613–620.
- "The Image of Absence: Archival Silence, Data Visualization, and James Hemings" by Lauren
  Klein in *American Literature* (2013) 85.4: 661–688.

Worksheet 6

## Course Requirements & Grading

- 25%     Class and online participation
- 25%     Weekly worksheets
- 25%     Final exam
- 25%     Final paper / project

