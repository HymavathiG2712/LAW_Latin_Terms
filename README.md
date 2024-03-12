# Information Extraction

**Data Collection and Understanding:**

Gathered the Excel sheet containing legal Latin phrases and the PDF files containing case documents from the Supreme Court of Indiana.
Understood the structure and content of the data, including the format of the Excel sheet and the layout of the PDF documents.

**Data Preprocessing:**

Converted the PDF documents to text format for easier analysis.
Cleaned and preprocessed the text data to remove irrelevant information, such as headers, footers, and page numbers.
Loaded the legal Latin phrases from the Excel sheet into a data structure for matching.

**Exploratory Data Analysis (EDA):**

Explored the text data to understand its characteristics, such as word frequency distributions, common patterns, and relevant features.
Visualized the data using charts and graphs to gain insights into trends and patterns.

**Feature Extraction:**

Used regular expressions or other text processing techniques to extract relevant features, such as case names, citations, judge names, and Latin phrases, from the text data.
Counted the occurrences of each Latin phrase in the text files.

**Data Analysis:**

Analyzed the extracted features to answer specific questions or address the project objectives, such as identifying the most frequently occurring Latin phrases, determining the distribution of citations across cases, analyzing trends in judge names or case years, and examining the relationship between Latin phrases and case outcomes.

**Output and Visualization:**

Generated visualizations, summary statistics, and reports to communicate the findings of the analysis effectively.
Created a CSV file or other structured output format containing the results of the analysis, such as the frequency of Latin phrases, case names, citations, judge names, and years.

**Validation and Interpretation:**

Validated the results of the analysis against known information or expert knowledge to ensure accuracy.
Interpreted the findings in the context of the project goals and objectives, drawing meaningful insights and conclusions.

**Documentation and Reporting:**

Documented the entire data analysis process, including data preprocessing steps, feature extraction techniques, analysis methodologies, and key findings.
Prepared a comprehensive report or presentation summarizing the project methodology, results, and recommendations.
Shared the document with the client.


STAR: 


**Situation**:

Tasked with developing a data extraction system for legal documents from the Supreme Court of Indiana.
Documents were in PDF format and contained case details like names, citations, judge names, and Latin phrases.


**Task**:

Extract structured information from PDF documents including case names, citations, judge names, and Latin phrases.
Count the frequency of Latin phrases across all documents.

**Action**:

Used PyPDF to convert PDF documents into text files.
Developed regular expressions to accurately extract case names, citations, and judge names.
I was given a list of 5725 legal Latin phrases and used regex to search for their occurrences within the text files.
Utilized Pandas for data processing and analysis, organizing extracted information into a structured format.

**Result**:

Successfully extracted desired fields from all 100 PDF documents, totaling 8642 text files.
Accurately identified case names, citations, judge names, and presence of Latin phrases.
Output CSV file provided comprehensive overview, including frequency of each Latin phrase across all documents.
Project streamlined analysis process and provided valuable insights for further research and analysis.




