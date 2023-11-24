## Natural Language Processing (NLP): E-commerce Text Classification

### Text Classification
Text classification is a widely used natural language processing task in different business problems. Given a statement or document, the task involves assigning to it an appropriate category from a pre-defined set of categories. The dataset of choice determines the set of categories. Text classification has applications in emotion classification, news classification, spam email detection, auto-tagging of customer queries etc.

### Objective
The objective of the project is to classify e-commerce products into four categories, based on its description available in the e-commerce platforms. The categories are: Electronics, Household, Books, and Clothing & Accessories.

### Data
#### Dataset : https://zenodo.org/records/3355823

The dataset has been scraped from Indian e-commerce platform(s). It contains e-commerce text data for four categories: Electronics, Household, Books and Clothing & Accessories. Roughly speaking, these four categories cover 80% of any e-commerce website, by and large. The dataset is in .csv format and consists of two columns. The first column gives the target class name and the second column gives the datapoint, which is the description of the product from the e-commerce website. We insert column names and swap the columns, to put the target column at the right.

