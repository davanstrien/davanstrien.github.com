---
layout: Post
category: LAPIS
tagline: "Digital Typesetting"
tags : [technology, form and content, publishing, nerdy]
---

I was unsure how to go about this weeks blog. The lecture covered a broad range of potential topics making it difficult to decide how to draw all of these different areas together. What I have instead decided to do is pursue the topic from a slightly different (perhaps super nerdy!) angle.

## Technology: Mediating form and content?

One of the readings for the lecture discussed different conceptions western and Chinese history had taken to the development of printing. Western history has largely focused on the role of printing in the development of print cultures. This has led to an understanding of the technology of books and other printed materials as being about the printing press. In *The Woman Who Invented Notepaper*, T.H. Barrett (2011) highlights the different potential understandings of what is a technology. Barrett describes how Xue Tao developed a new size of paper which suited a particular form of poetry she was writing. In this example an existing technology, paper, was developed to suit a new need. This new development in technology in turn allowed for further innovation in artistic content.

The western historiography in contrast emphasises much more strongly the development of the printing press as playing a key role in the development of printing cultures. It was the Gutenberg press and subsequent printing presses which are understood as the innovators - in the case of Chinese historiography paper itself is given a stronger emphasis. The example of Xue Tao developing new sizes of paper (form) in order to publish a particular type of content (shot 40 character poems) led me to think of other similar (more) contemporary examples. A similar example sprung to mind in the form of TeX and LaTeX.

## Tex Document preparation System

### What is TeX?

>'LaTeX is a document preparation system for high-quality typesetting. It is most often used for medium-to-large technical or scientific documents but it can be used for almost any form of publishing.' [LaTeX Project.org](http://latex-project.org/intro.html)

### A brief history

In a similar way to the need Xue Tao had for a new technological tool for a specific artistic purpose, the development of TeX also responded to a particular need. TeX was developed by Donald Knuth in the late 1970s in response to receiving disappointing galley proofs from the printers for a book he was due to publish.

During this period the possibility for printing for digital files existed and so, being a computer scientist (and mathematician), Knuth sought to address the problem. The way Knuth went about doing this was by trying to understand the rules of good typesetting mathematically and in turn implement these rules in a computer program. Although initially intending to be complete with the project within 6 months but in the end the project took around 10 years. In 1978 TeX was released. Subsequent developments during the 1980s developed TeX into LaTeX. So what exactly does LaTeX try and do?

### The aims of TeX

The aim of TeX are essentially to allow someone to produce high quality typeset documents electronically. There are some important differences between what LaTeX tries to do compared to a wordprocessor like Microsoft Word or Open Office. Instead of trying to write the text in the way you want (hope) it will appear, LaTeX uses markup to indicate the structure and formatting of the text. The software then makes the decisions about how to best layout the text. In this way LaTeX aims to put allow the writer to focus on content and the software to focus on the form.

Other important features of LaTex includes support for easily writing mathematical functions, system independence, stability (LaTeX documents written 20 years ago will appear exactly the same today as then, word documents created a couple of years can often be difficult to open), and the ability to work with large documents very easily. There are many other features but that is perhaps a discussion for another post.  

### Why is typography important?

There are many different reasons why typography is important. There are ample studies and examples. At the most basic level documents which feature poor typography are difficult to read. Sometimes this might be very consciously experienced, however there are also instances when you might feel like a document looks 'nice' and not really be aware of the exact reasons why. There have been a [number](http://www.mdgadvertising.com/blog/how-typefaces-influence-perception-and-persuasion/) of discussions about the way in which typesetting can influence the perception of documents.

A particularly interesting resource on why typography is important is an online book, [*Practical Typography*](http://practicaltypography.com). The book itself is interesting in being published online as an experiment. The book lays out some common rules for typography and explains [why](http://practicaltypography.com/why-does-typography-matter.html) it is important.

One of the main opportunities software like LaTeX allows is the ability for very professional looking self-publishing. One of the problem with a lot of self-published material (and unfortunately often professionally published material) is that the presentation can be quite poor. This is going to be especially likely to happen if Word is used to produce a pdf which is then used as a basis for the book. Although some might argue that content should be able to stand on its own, bad formatting can be incredibly distracting. With a piece of software like LaTeX or its derivatives its very easy to present your content in a pleasing way without much energy or without an in-depth understanding of typesetting. A [post](http://www.thebookdesigner.com/2010/01/the-trouble-with-word-processors/) on the Book Designer website outlines the importance of this for self-publishers.

I will try to write a separate post on some ways to make use of LaTeX and other approaches to writing documents which focus on the content (however dubious that may!) and not allow technology to worry about the content. In the meantime here are some potential resources if you are interested:

* [Getting to Grips with LaTeX](http://www.andy-roberts.net/writing/latex/benefits)

* [A slightly polemical take on the problem with wordprocessors](http://ricardo.ecn.wfu.edu/~cottrell/wp.html)

* [An article on the beauty of LaTeX](http://nitens.org/taraborelli/latex)
