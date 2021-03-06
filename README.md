<img src="https://github.com/Naviden/database_mapping/blob/master/Images/logos.png" height="300" align="center">

# Academic Database Mapping

As a part of the _Literature review: how to build a good bibliography_ course in my PhD, I tried to map the following features for 6 of mostly used databases the Academia.
These feature are:
- what topics the database is best suited
- The list of journal and books indexed (and whether they are available in full-text or bibliographic format)
- The update rate, i.e. how long the new releases take to be included in the index
- Whether the resource contains also open access literature
- What kind of document this resource includes (peer reviewed journals, magazines, books, encyclopedias, thesis, papers, preprints, reports etc.)
- How easy and friendly the interface is, whether it allows a more refined search according to different information needs
- Availability of Thesaurus, subject headings set up automatically, filters, classifications, “cited by” and cross-reference indexes etc.
- Quality of the ranking by relevance

The databases are:
- ACM Digital Library
- ArXiv.org
- Wiley Online Library Journals
- Scopus 
- CiteSeerX
- ScienceDirect

To answer to the second point, At first, I tried to create a simple scrapper, which partially worked for _ACM Digital Library_ but I wasn't able to scrape the rest of the databases as for some cases like _Wiley Online Library Journals_ machine access was denied or _ArXive.org_ which doesn't have such structure (a list of journals,...)

## What you find in the repository

- _description.docx_ has the mapped points for each database
- _databases folder_ : for some of sources there are additional files(csv, json, Py, ...) about their content, either scrapped or downloaded directly from their site
  
## Note
To evaluate the quality of ranking relevance, I used the following phrase:
_natural language generation explainable ai_