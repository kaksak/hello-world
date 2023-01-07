# Hello World
## Baby steps into the world of collabortive coding


I'm a student at PSU, breaking into the use of Markdown for coding documentation. I'm using this document to test out some of the features. [Dillinger](https://Dillinger.io) is helping me see what this looks like when rendered.

- I may have used this with RStudio in the past
- I would like to learn how to use this with both Python and R
- Learning how to weave together Markdown and Python/R into PDF documents would be handy for client communication

## Childhood
*Introductions can be awkard. Isolated coders excel at awkard, as demonstrated in my attempt at a bio:*

- Born on the banks of the St.Croix River
- Preferred to be in the water or in the snow
- Liked people almost as much as books
- Valued intelligence and kindness

On a never-ending journey toward adulthood, I have learned that boundaries to achievement are almost always self-imposed.
Wisdom from the [Wizard of Oz](https://en.wikipedia.org/wiki/The_Wizard_of_Oz_(1939_film)):

> GLINDA:	You don't need to be helped any longer.
>	You've always had the power [to do what you want to do]

> DOROTHY: 	I have?

> SCARECROW: Then why didn't you tell her before?

> GLINDA: Because she wouldn't have believed me. She
> 	had to learn it for herself.

## Current Quest

My mission is to become a competent coder and produce documented products for clients:

- **R scripts** - Statistical analyses with methods documentation for publicaion
- **ArcGIS Scripts** - Toolboxes with scripts for loading into ArcGIS Pro
- **Web Apps** - Web-based applications using ESRI software
- **Python Scripts** - Stand-alone Python applications for data manipulation
- **Mobile Apps** - Configured mobile apps for spatial, scientific data collection
- **Databases** - Much like a closet organizer, clean, organize, document and store data in databases

## Using Markdown

I can see clear benefits in using Markdown to document code- especially when code can be called directly from the document. It is my understanding that if I put a code chunck inside the right delimiters, it can be read when the file is run by a particular program. For example:

**R script:**

```r
x <- "Hello World"
print(x)
```

**Python script:**

```p
x = "Hello World"
print(x)
```

Note: This is what I'm HOPING to do. I don't even know if this is even the right way to do this. 

## Similarites to Past Experience 

In the foggy past, I used Markdown or something similar with embedded R code chunks and a LaTeX handler that turned it all into a PDF. The example table below looks very similar to something I would have done in that realm. In the text of the Markdown, I was able to write content that referenced variables from the code. A little bit like hyperlinks (see below), but pointing to a variable in the code (be it Python or R). This allowed the write up to update automatically with changes to the data or analysis.

| Plugin | README |
| ------ | ------ |
| Variable 1 | [variable 1][PlDb] |
| Varoable 2 | [variable 2][PlGh] |
| Variable 3 | [variable 3][PlGd] |

Ideally, the equivelant of LaTeX would produce a PDF with a rendering similar to what I see in Dillinger. I remember LaTeX allowing fairly complex tables to be created, which is critical for producing complex tables for publication, or for just displaying relatively complex data tables. 

## Images

I would also like to be able to use Markdown and various programming languages in combination to produce write ups that include images. Specifically, graph outputs from R and map outputs from Python. A dynamic approach is preferred, where the PDF is rendered as the code is producing new output.
