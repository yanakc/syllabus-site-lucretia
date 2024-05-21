# Challenging Conventions: Lotto'sLucretia

A visual exploration of Lorenzo Lotto's enigmatic depiction of Lucretia: In this captivating painting, Lotto challenges the norms of his time by portraying a woman in a manner deemed unconventional for a Renaissance lady. 

*This visualization is based on the article “Lotto’s Lucretia” by Rona Goffen from the Renaissance Quarterly journal vol. 52, no. 3, 1999.*


<img src='img/Lucretia_Bild.jpg' class='noresize'>

[Portrait of a Woman Inspired by Lucretia, Lorenzo Lotto, c. 1533, oil-on-canvas, 96 cm × 110 cm,  National Gallery London](https://www.nationalgallery.org.uk/paintings/lorenzo-lotto-portrait-of-a-woman-inspired-by-lucretia)



Scroll along to find out who was Lucretia, what are the key elements of the painting and why is it unconventional.


---


## Why 

In the realm of design education and research, there's a common emphasis on outcomes—be it presentations, prototypes, or papers. This focus, while essential, tends to sideline the  exploratory and dynamic process leading to these results. The journey to the final projects is marked by twists, turns, and tangents. This is where much of the learning and discovery occurs. 


*Syllabus Site* was conceived as a tool to highlight and document these critical but frequently overlooked aspects of design projects. It serves as a dynamic interface chronicling the voyage through readings, workshops, and discussions.


This approach not only retains but celebrates the meandering nature of design as an intellectual journey, ensuring that the wealth of inspirations—from historical examples and theoretical frameworks to contemporary projects and research studies—is preserved and made accessible. 


---


## What

A *Syllabus Site* is a one-page website arranging its elements along sections that can be scrolled vertically.


### Design

The webpage is designed with the aim to open an evocative information space, where the sources that foster creativity, dialogue, and learning can be gathered, recapitulated, and appreciated. The monolithic structure of conventional documents is broken up, by introducing a relational quality to the connections between sections and items.


### Structure

There are two main types of elements:

- **Sections** – Larger blocks gather the material for weekly course sessions.
- **Items** – Smaller elements feature images, text, and other content.

Each item is connected with its section by a thin line. The navigation (≡) gives access to all sections.

The last section acts as the footer, where the typical array of logos and links belongs.


### Examples

The template is in use to document the following [Interface Design](https://interface.fh-potsdam.de) courses offered at [FH Potsdam](https://www.fh-potsdam.de/):

- **[Decolonizing Data Visualization – Visualizing Postcolonies](https://infovis.fh-potsdam.de/decolonizing/)** (Summer 2022)
- **[Organigrams for/from the future](https://infovis.fh-potsdam.de/organigrams/)** (Summer 2023)


<img src='img/decolonizing.webp' class='noresize'>

[Decolonizing Data Visualization – Visualizing Postcolonies](https://infovis.fh-potsdam.de/decolonizing/)


<img src='img/organigrams.webp' class='noresize'>

[Organigrams for/from the future](https://infovis.fh-potsdam.de/organigrams/)


---


## How

The *Syllabus Site* template can be easily used with minimal technical requirements.


![](img/sidebyside.webp)  
Page content and source side by side


### Get started

1. Download or clone the [GitHub repository](https://github.com/uclab-potsdam/syllabus-site/)
2. Give your page a title, fill out open graph fields, and adjust theme color in `index.html`
3. Add your content into `README.md` and `img/`


### Files

The template has the following file structure:

      img/
      index.html
      src/
      README.md

The `README.md` file contains all the textual content of your page and references the images that you need to add to the `img/` directory. 

The `index.html` file connects template and your content; here you need to make a few edits to add title, description, and preview of your webpage. 

You do not need to change anything within `src/`, which contains the internal files of the template.


### Syntax

The `README.md` uses the [Markdown](https://en.wikipedia.org/wiki/Markdown) format, a markup language used by many platforms including GitHub.

There are two conventions we introduce to distinguish and connect sections and items:

- **Sections** are delineated by a horizontal rule `---` 
- **Items** are separated by two empty consecutive lines

Each section should contain a heading:
`#` for primary, `##` for secondary, and so on.

To exclude a section from the navigation menu, include `<!--skipnav-->` at the start of the section.



### Things to consider

- Include an expressive preview image `img/cover.png` so that your page can be previewed on social media and messaging apps.
- Given that your webpage might be accessed from a mobile device with a slow connection make sure to optimize image file sizes.


---


## Who

*Syllabus Site* was put together by [Philipp Proff](https://philippproff.eu) and [Marian Dörk](https://mariandoerk.de) with the helping hands from many people.


**Markdown munching**: [Marked](https://marked.js.org) by Christopher Jeffrey


**Terrific typeface**: [HK Grotesk](https://github.com/HankenDesignCo/HK-Grotesk) by Alfredo Marco Pradil


**Friendly feedback**: Myriel Milicevic, Lamin Manneh, Fidel Thomet, Mark-Jan Bludau, Sabine de Günther and Francesca Morini


**Yes, you!**: Syllabus Site is [made available](https://github.com/uclab-potsdam/syllabus-site/) under the liberal MIT license. Feel free to reuse and revise it!


---


[<img src='img/fhp.svg' style='height:2.25em'>](https://www.fh-potsdam.de/) 
[<img src='img/id.svg' style='height:1.75em'>](https://interface.fh-potsdam.de/) 

[Contact](mailto:marian.doerk@fh-potsdam.de,philipp.proff@gmx.de?subject=Syllabus%20Site) · [Imprint](https://www.fh-potsdam.de/impressum) · *This is a [Syllabus Site](https://infovis.fh-potsdam.de/syllabus-site/)*
