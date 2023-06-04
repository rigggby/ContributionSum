# ContributionSum
Sample from the ContributionSum Dataset
## Dataset Format
Each paper is represented as a key-value pair where the key is its arxiv id and the value contains the following fileds
* structure: list of section titles (and its subsection titles if presented)
* title: title of the paper
* abstract: abstract of the paper
* prompt: detected contribution prompt
* extracted_contribution: list of author-written contributions
* contribution_types: types of extracted contributions based on our annotation scheme: 0 - Approach, 1 - Result, 2 - Analysis, 3 - Topic or Resource
* SECTION_TITLE: full text from a specific section
