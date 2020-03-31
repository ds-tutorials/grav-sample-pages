---
title: 'File Naming Conventions'
media_order: yellowstone.jpg
date: '02-08-2019 00:00'
taxonomy:
    category:
        - blog
    tag:
        - 'landscape photo'
        - 'the carpentries'
        - yellowstone
hero_classes: 'title-h1h2 text-light overlay-dark-gradient'
hero_image: yellowstone.jpg
feed:
    limit: 10
---

I have always had a difficult time naming things - whether it is an essay for a class, a character in a story, or even a simple file or folder on my computer. There are so many possible names, and it can feel overwhelming trying to make sure I choose the best name.

===

Fortunately, there are three principles for naming files that can make coming up with the right name considerably easier.

## Machine Readable

Files are stored on computers, so they should be named in ways that the computer can understand.

- Avoid spaces, punctuation, and accented characters.
- Do not make file names case-sensitive - that is, do not name one file _my-file.txt_ and another one _my-File.txt_.
- Use delimiters like hypens "-" and underscores "\_" deliberately. Or just use them to make sure your eyes don't bleed.

Avoiding spaces might seem difficult, but there are two excellent ways to have effective multi-word titles without spaces.
- Use hyphens or underscores to separate words: _my-file.txt_ or _my\_file.txt_.
- Use camel case - every word after the first word is capitalized: myFile.txt

## Human Readable

There is really only one primary requirement for a file to be human readable: The name should provide information about the file contents, the more specific (without being ridiculous long) the better.

If you are writing the first draft of a research paper, for example, the most uninformative name you could choose would be something like _untitled.txt_. Only slightly better are names like _paper.txt_ or _first-draft.txt_. The best name would include some kind of version information, perhaps the date you wrote it, as well as information about the actual contents of the paper that would differentiate it from any other paper you have written or might write in the future. So if you started work on this particular draft on January 1 2020 and the paper is about why libraries are great, an excellent title might be _why-libraries-are-great_2020-01-01.txt_ or _2020-01-01_why-libraries-are-great.txt_.

## Using Default Ordering

Mostly this comes down to letting the system order your files logically based on numbers - for example, sorting your essay drafts based on date. There are a lot of different ways you might do this depending on what exactly you want, but there are two things to keep in mind when using numbers and dates to order files.

1. **Pad numbers with 0.** 3 will generally be listed after 20, because 3 comes after 2. However, 03 will always come before 20. If you are using numbers, make sure to use the same number of digits for each number, adding 0 as necessary.
2. **Use they year-month-day (YYYY-MM-DD) format for dates.** This will allow the system to sort your files accurately based on the date. Imagine three files created on March 10 2018, January 1 2019, and December 23 2019. Using a format like MM-DD-YYYY, trying to sort the files in descending (most recent) order would yield: _12-23-2019_words.txt_, _03-10-2018_words.txt_, _01-01-2019_words.txt_. Semantically, this order makes little sense - a file written in 2018 is listed between two files written in 2019. Using YYYY-MM-DD would instead order the files as: _2019-12-23_words.txt_, _2019-01-01_words.txt_, _2018-03-10_words.txt_. This is much more logical and convenient.

## The Carpentries

There are many advantages to following file naming conventions or best practices. For more information on these advantages, as well as the practices themselves, read the Data Carpentry lesson [File Organization: Naming](https://datacarpentry.org/rr-organization1/01-file-naming/index.html). The Carpentries teaches foundational coding and data science skills through Data Carpentry, Software Carpentry, and Library Carpentry lessons. Check out their [website](https://carpentries.org/) or take a look at the [schedule](https://libraries.ou.edu/content/software-and-data-carpentry) for workshops offered by OU Libraries.

## Credit

The material for this post comes from the Data Carpentry lesson [File Organization: Naming](https://datacarpentry.org/rr-organization1/01-file-naming/index.html). All lessons are copyright of [The Carpentries](https://carpentries.org/), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode).

Photo: Yellowstone by [Wendy Acker](https://www.flickr.com/people/theodwynn/), [CC BY-NS-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)