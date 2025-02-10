# 608_ERModels
This project implements the design for HW2 for CMSC 608.

Rendered pages for this project are available at [https://quoll.github.io/608_ERModels/](https://quoll.github.io/608_ERModels/).

## Report
The submissible report is in the file [`report.html`](https://quoll.github.io/608_ERModels/report.html). This was build from the `report.qmd` file using [Quarto](https://quarto.org/).

The requirements of this assignment included using [Mermaid](https://mermaid.js.org/) for the Crow's Foot ER digrams, and [Graphviz](https://graphviz.org/) for the Chen ER diagrams. These are very limited in the types of diagrams they can produce, with substandard results. During class, the students were generally invited to use any drawing package, so a separate version of the report is also included, with embedded images (generated using [draw.io](https://draw.io)). The source for this is in the file `index.qmd`, and the rendered HTML is available [here](https://quoll.github.io/608_ERModels/). The content of the reports is the same, but the images are different.

While the [submitted file](https://quoll.github.io/608_ERModels/report.html) is what the assignment called for, the [fully rendered report file](https://quoll.github.io/608_ERModels/) is the preferred version.

## Design
The report includes the design for three different ER models:
* Library Management System
* School Course Enrollment System
* Hotel Booking System

### Discussion
Each system is first described in a discussion section, where the entities are identified and each of their attributes considered. The relationships between the entities are then described, and the ER diagrams are presented.

### ER Diagrams
Both Crow's Foot and Chen ER diagrams are presented for each system. The main report renders these using Mermaid and Graphviz, but include links to the draw.io versions. While the images can be embedded easily, this would not show the diagrams for anyone inspecting the file directly.

### Schema
At the end of each section, a schema is presented, using a syntax similar to SQL, to show how the ER model could be implemented in a relational database. This is not a complete schema, but rather a starting point for a database designer. The schema requirements of the assignment reference material from the course, but as of submission this has not been available. To compensate, a common schema syntax has been adopted.

## Outcome
As this project is entirely about design, there are no runnable components, beyond the report generation by Quarto.

## Tools
All of the tools used in this project are open source, and are available for free. They are:

* [Quarto](https://quarto.org/). This is a markdown-based document generation tool, which can be used to generate HTML, PDF, and other formats. It is particularly useful for generating reports that include code, as it can run the code and include the output in the report.
* [Mermaid](https://mermaid.js.org/). This is a tool for generating diagrams from text descriptions. It is particularly useful for generating ER diagrams, as it can generate Crow's Foot diagrams, automating the layout for a given structure.
* [Graphviz](https://graphviz.org/). This is a tool for generating diagrams from text descriptions. It can render `dot` graph files, including formats for generating Chen ER diagrams, automating the layout of the graph.
* [draw.io](https://draw.io). This is a general drawing tool that can be used to generate a wide variety of diagrams, using web standards. It is significantly better at generating ER diagrams than the previous tools, though it requires manual drawing without any understanding of the roles of of the image elements.

## License
This project is licensed under the Create Commons CC0 1.0 Universal License - see the [LICENSE](LICENSE) file for details.
