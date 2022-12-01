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
structures at scale, visible across long-distances, through corpora and archives. No prior
experience is necessary to participate: the only course requirement is interest in language,
history, and technology.

## Course Structure

3 hour sessions, 2 times a week, for 6 weeks.

Depending on the week, our time in class (and out) will be divided between two types of
activities:

- First, with the emphasis on discussion of assigned reading materials.
- Second, with the emphasis on active in-class excesses, including formal analysis (done by
  hand, or with an aid of a computer, depending on individual interest / capability).

## Provisional Schedule & Reading List

### Week 1: Letter

What is a letter? The history of alphabets. Glyphs and hieroglyphs. Telegraph codes. Character
encoding. From memory to pixel.

### Week 2: Word

Word boundaries. Parts of speech. Types and tokens. Spelling and misspelling. Counting words.

### Week 3: Sentence

Syntax. Sentence clause structure. Punctuation. Chain generators.

### Week 4: Paragraph

Patterns and arrangements. Style guides. The sh

### Week 5: Story

Visualizing stories. Context persistence.

### Week 6: Collection, Archive

Historical and institutional context. Sample bias. Corpus analysis.

## Course Requirements & Grading

- 25%     Class participation
- 25%     Weekly short writing responses
- 25%     Final exam (designed to reward regular, attentive reading)
- 25%     Final paper / project

## University Policies

When in doubt, cite! Plagiarism is insulting to your fellow students, your instructors, and to
the research community at large. It wastes my time and yours, and is, ultimately, not worth the
risk. Consult Columbia’s guidelines at <http://www.college.columbia.edu/academics/integrity> or
ask me for help early in the writing process.
