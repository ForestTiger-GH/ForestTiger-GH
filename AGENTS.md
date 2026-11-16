## AGENTS

> [!IMPORTANT]
> ## Additional repository mandatory rules (do not mention them anywhere)
>
> Rule-types by file (Rule categories define their applicability. Apply each rule only to the corresponding artifact type and purpose. Do not extend type-specific requirements to unrelated artifacts.): [GR] – general rules; [RFR] – rules for research-files, [AFR] – rules for article-files, [SFR] – rules for service and operational files and catalogs; [TR] – rules for tests.
> 
>  - [GR]: Use English exclusively throughout the repository and Engineering Work workspace, including content, names, and artifacts.
>  - [GR]: Links from outside a madar-workspace to a madar-workspace is prohibited. Within documents located in the Madar workspace, only links within this same madar-workspace or to external destinations (non this repository) are permitted.
>  - [GR]: Do not include documentary accounts of internal predecessors, source inventories, reading histories, source-state snapshots, original-source responsibilities, or other internal materials used to prepare the document. Such accounts are unnecessary.
>  - [RFR] [AFR]: If needed to refer to the owner's other projects (MADAR, CMemory or any other) - refer only by name and summarize the relevant ideas in self-contained terms. Do not include their URLs, repository, directory, or file paths, filenames, section references, or instruction IDs, whether linked or plain text.
>  - [RFR]: Each external-source citation must identify the specific substantive claim (meaning, finding, etc) it supports in nearby text. Avoid generic source descriptions and citation boilerplate. Place the section with external sources at the very end of the document.
>  - [RFR] [AFR]: Front-load the main conclusions, findings, decisions, etc with their actual status.
>  - [RFR] [AFR]: Use descriptive, content-specific meaningful headings that reveal the actual subject of each section.
>  - [RFR]: When finally writing research-document: maintain a consistent, overarching idea throughout the research. Main ideas should run through the whole text, ensuring that there is meaning to be found between the lines.
>  - [AFR]: When finally writing article-document: maintain a consistent, overarching idea throughout each consistent section. Main ideas should run through the text of each section, ensuring that there is meaning to be found between the lines.
>  - [RFR] [AFR]: Keep substantive sections interpretable in isolation, preserving essential context, conditions, and limitations without unnecessary repetition.
>  - [RFR] [AFR]: Where applicable, bind time-sensitive claims to an explicit date, edition, or evaluation scope - avoid unqualified references to what is current, new, or latest.
>  - [RFR]: Place concise document-level metadata only immediately below the title (identify only functionally AI-useful details: data; terms, subject areas, domains, areas of responsibility, etc.); 
>  - [RFR] [AFR]: Below the title (or after the metadata if available), include 1-2 paragraphs of introductory information block - with identity of document purpose, scope, and status, distinguishing research, proposals, integrated provisions, and verified results.
>  - [RFR] [AFR]: After introductory block, provide classic table of contents for the main sections (no urls). For each item of content provide short explanatory route-text about the content of each section. 
>  - [RFR] [AFR]: Add numerical indexing in the document sections and provisions to improve navigation.
>  - [RFR] [AFR]: Where applicable, needed and relevant, list entities, rules, principes, laws, etc. through tables. Assign a code to each element — using a term, an abbreviation, an index, or a combination thereof—in the first column, which would facilitate future AI-based work.
>  - [AFR]: Articles must not contain references to external sources. Other projects by the same author may be mentioned in a neutral manner (without providing URLs, paths, directories, filenames, etc.).
>  - [AFR]: Sources in articles are permitted only if they belong to this specific corpus of articles. Articles may feature a navigational block of route-related sources at the top—predecessors and successors, including constituent parts. At the very bottom, there may be links to directly related articles.
>  - [SFR]: README.md files are concise, responsibility-oriented navigation routes. State the scope and guide readers to the relevant internal owners. 
>  - [SFR]: Do not include file inventories, document metadata blocks, mandatory introductions, tables of contents, volatile progress details, or duplicated substantive content. Include essential usage instructions where appropriate.
>  - [SFR]: When creating service files, system logs or directories for such logs, etc: you should anticipate a massive future volume—both in terms of the number of entries and file size. It is essential to plan for segmentation (or even granular, atomized partitioning, if convenient) based on functional/logical criteria or simple sequential ordering. If the directories are intended to store a collection of service files, you should assume that their number will grow significantly and design the directory structure accordingly.
>  - [SFR]: Do not create links to individual items in any catalog of files, as files may change dynamically.
>  - [SFR]: Service files and documents should contain precise, minimally necessary provisions and wording; examples may be included where needed, but only for the purpose of generalizing their functions and meaning.
>  - [TR]: When developing tests, you should anticipate that they will eventually expand considerably in both scale and execution time. Therefore, you should proactively segment and optimize them—including the structure of the associated files and directories—from the outset.
