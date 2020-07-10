# Covid Graph CVD and Drug Association
Covid Graph exploration with CVD and Drug association

**Title**: A study of Covid-19 KG for Drugs and CVD cases

<img src="https://covidgraph.org/img/content-img/data_model_with_logos_and_numbers.png" width="500" height="250"></img>)

<center> Image Courtesy: covidgraph.org </center>

**Description**: Covid-19 is caused by a coronavirus called SARS-CoV-2. It is believed that this virus has a pivotel interaction with the renin-angiotensin-aldosteron system to enter cells in the body. Accordingly, concerns exist that certain CVD drugs such as angiotensin-converting enzyme blockers (ACE inhibitors) and angiotensin receptor blockers (ARBs) may increase the susceptibility to SARS CoV-2 as well as the severity of Covid-19. In this project, the students will apply a text mining approach to create a Covid-19 KG for ACE inhibitors and ARBs and identify relevant underlying molecular pathways and mechanisms that may play a role in Covid-19.

### Participants
- Maya Gupta
- Alex Zhang
- Ethan Tran

Project Leaders/Instructors: 
Dr. Dibakar Sigdel & Dr. David Liem (Mr. Vincent Kyi for technical support)

Data Source: (www.covidgraph.org)


**Project walk-through**:
Identification of documents in the intersection with CVD cases, Covid 19 and drug category (defined by MeSH).
Analysis of outcomes from cypher queries in graph databases for different drug categories linking CVD cases and Covid 19.
Prepare a score based clustering approach for drugs to CVD complications and explore underlying molecular mechanisms. 
Organize codes and prepare project documentation sites at PingLab Intern GitHub account.
Final presentation at lab meeting.

**Education goals**:  The students will learn how to work with innovative tools in text mining and knowledge graphs (e.g., Neo4J and Spark) for data exploration and development of search algorithms for specific tasks in biomedical scenarios. 

**Scientific goals**:  To learn how to hypothesize meaningful biomedical questions from available tools and databases in CVD and Covid-19. (e.g., Which drug or drug category has a significant effect on the severity and mortality of Covid-19, and what are the underlying mechanisms?) The search results can be further explored to investigate underlying age based molecular mechanisms.


### Preparing Foundation
- Create an account at NLM/UMLS account
- Get Familiar with the following:
    - [MeSH tree](https://meshb.nlm.nih.gov/treeView): Madical Subject Headings
    - [ICD codes](https://icd.who.int/browse11/l-m/en): International Classification of Disease
    - [Uniprot](https://www.uniprot.org): Database of proteins organized with Protein ID, synonyms, Abbr, associated Genes and biomolecules
    - [Reactome](https://reactome.org) : Database of Pathways and associated documents in Graph structure
    - [Drugbank](https://www.drugbank.ca) : Database of Drugs and associated documents
- Install Python([Anaconda](https://www.anaconda.com/products/individual))
- Install [Neo4J](https://neo4j.com/) and take available tutorials
- Get Familiar with [NLTK](https://www.nltk.org/) NLP package in Python
- Get introductory idea of Machine Learning from [Scikit](https://scikit-learn.org/stable) Learn and [Tensorflow](https://www.tensorflow.org/) (Specially, LSTM)

### Project Detail


