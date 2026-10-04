---
title: Skilss github pages
description: Notes on genomics, sequence analysis and learning to code
---

<!--
  👆 The block between the two "---" lines is called FRONT MATTER.
  GitHub Pages (which uses a tool called Jekyll) reads it to set the
  page title and other settings. It is not shown on the page itself.

  This is an HTML comment. Anything between these markers is hidden
  on your website, so you can leave notes to yourself here.
-->

# Welcome to My Bioinformatics Blog 🧬

Hi! I'm learning bioinformatics and documenting what I discover along the way.
This site is built with **GitHub Pages**, and this page comes from a single
file called `index.md`.

<!-- A line starting with one # is the biggest heading. ## is smaller, ### smaller still. -->

## About this blog

Here I will write about:

- DNA and protein sequence analysis
- Working with tools like **BLAST**, **Python** and **R**
- Things I get stuck on, and how I solved them

<!-- Lines starting with "- " become a bullet list. -->

## What I'm learning right now

1. How GitHub Pages works
2. Writing in Markdown
3. Basic Python for reading FASTA files

<!-- Lines starting with "1. ", "2. " become a numbered list. -->

## A tiny example

Text can be **bold**, *italic*, or `inline code`.

A DNA sequence in FASTA format looks like this:

```
>example_sequence
ATGCGTACGTTAGCCTAGGCTAACGTTAGC
```

And here's a little Python that counts the bases:

```python
seq = "ATGCGTACGTTAGCCTAGGCTAACGTTAGC"
for base in "ACGT":
    print(base, seq.count(base))
```

<!-- Three backticks ``` start and end a code block. Add a language name
     (like python) right after the opening backticks for colored syntax. -->

## Useful links

- [GitHub Pages documentation](https://docs.github.com/en/pages)
- [Markdown guide](https://www.markdownguide.org/basic-syntax/)
- [NCBI](https://www.ncbi.nlm.nih.gov/)

<!-- Links are written as [text to show](web address). -->

## A small table

| Base | Name     | Pairs with |
|------|----------|------------|
| A    | Adenine  | T          |
| T    | Thymine  | A          |
| G    | Guanine  | C          |
| C    | Cytosine | G          |

<!-- Tables use | to separate columns. The second line with dashes is required. -->

> 💡 **Tip:** A line starting with `>` becomes a quote box like this one.

---

*Thanks for visiting! New posts coming soon.*

<!--
  NEXT STEPS TO TRY:
  1. Change the title in the front matter at the top and save (commit).
  2. Wait ~1 minute, then refresh your site to see the change.
  3. Add a picture: upload image.png to your repo, then write
     ![description of image](image.png)
  4. Create a second page, e.g. about.md, and link to it with
     [About me](about.md)
-->
