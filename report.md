---
layout: default
---

## Project methodology and Report

This section describes the methodology, tools and data sources used to create the story with the **Melody** tool. The website was then developed to present the information.

---

### Tools and workflow

The project followed a structured process combining creative generation and semantic data integration.


1.  **Music data retrieval and analysis:** I used the **Polifonia Corpus** tool in combination with the **MusicBO** module to access and analyse specific music data, discovering the information on which to base my story.
2.  **Semantic data integration:** To add rich, verified contextual information (e.g. details about composers, works or historical events), I queried the semantic knowledge bases **DBPedia** and **Wikidata** through federated queries.
3.  **Creative generation:** The next step was to use the **Melody** tool to generate stories. This tool was essential in providing an initial narrative or thematic basis on which to build the story and offered various tools, including graphs, tables, interactive maps and more.
4.  **Website development:** the final product was implemented as a **website** for presenting the story and associated data. The hosting and version control platform used was **GitHub Pages/Repository**.

---

### Data Sources

The information and content used in this project comes from the following main sources:

* **Melody:** Tool for generating the story.
* **Polifonia Corpus / MusicBO:** Specific data on the musical domain and its entities.
* **DBPedia and Wikidata:** Interconnected knowledge bases (Linked Data) for information retrieval, used to contextualize the stories. 
* **Git Hub:** To create the web site. 

---

### Challenges Encountered and Solutions

During the project, various challenges were encountered and resolved through careful consultation of documentation and community resources.

| Challenge | Description | Solution |
| :--- | :--- | :--- |
| **Data management with SPARQL queries** | The main difficulty was efficiently and correctly formulating **SPARQL** queries to extract the desired information from DBPedia and Wikidata. This was crucial to obtaining the semantic data necessary for creating the story. For example, when querying Wikidata for information on Chopin’s compositions, the results also included performances of his works by other artists.  | The difficulty was overcome through an in-depth study of the official DBPedia and Wikidata **documentation**, supplemented by consulting specific **forums and tutorials** on the SPARQL language to resolve syntax and optimisation issues. In this example, by applying the “by” filter: FILTER(CONTAINS(?catLabel, "by") it was possible to restrict the results to Chopin’s original compositions only.|
| **Melody's limitations** | For example, it took some time to understand that images were limited to the **JPG** format, and **repositioning** elements after their creation (e.g. tables, graphs, and text boxes) was not always working, resulting to be time-consuming. | The challenge was solved through patiently experimenting and researching in order to find a solution. |
| **Website Definition and Development** | The correct insertion of elements and structuring of the website **layout** caused compatibility and display issues. | Similarly, these bugs and specific problems were resolved by rigorously consulting the reference **documentation** (e.g. GitHub Pages, HTML and CSS) and actively searching for solutions on **forums and web development communities** (e.g. Stack Overflow). The website **W3Schools** was particularly useful to learn more about HTML and practice, together with CSS frameworks like **Bootstrap**. |













