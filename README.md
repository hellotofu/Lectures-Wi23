# Lectures-Wi23
For the Winter 2023 COGS108 course taught by Alex Simpkins Ph.D. These will be materials used during lectures. Mostly slide PDFs & Jupyter notebooks. 

Course materials are organized by week.

|Week  | General Topic  |
|---|:---|
| 01 | Introduction to Data Science  |
| 02 | Version Control & Data  |
| 03 | Data Ethics  |
| 04 | Data Analysis |
| 05 | Inference |
| 06 | Text Analysis  |
| 07 | Machine Learning  |
| 08 | Geospatial Analysis |
| 09 | Dimensionality Reduction  |
| 10 | Data Science Communication & Jobs  |


---
## License

The content of this project itself is licensed under the [Creative Commons Attribution 3.0 Unported license](https://creativecommons.org/licenses/by/3.0/), and the underlying source code used to format and display that content is licensed under the [MIT license](https://github.com/github/choosealicense.com/blob/gh-pages/LICENSE.md).

--

## Version Control Week 2 (slides will be on github/cogs018/lectures) - 1/17
- clone repositpry to local from remote 
- must add files to project 
- after chnages comit in local --> push changes to remote
- can create a branch in the repository 
- can fork repository (can work on repository) - merge changes in with pull request 
- look into OH 

## cont. 
- due friday (1/20 @ 11:59pm): project survey 
- due friday (1/20): lecture quiz 
- due next wednesday (1/25): D1 and A1 
- group will recieve github invitation to own repository 
- due friday of week 2 (5%): group will will be assigned project to review (google form) 
- github repo (8%) - due friday (?)

## Notes 
- Objective of group project 
  - identify the problems and goals of a *real* situation and dataset 
  - choose appropriate approach for formalizing and testing the prblems and goals and articulate the reasoning for that selection 
  - implement analysis choices on the dataset
  - interpret the results of analyses
  - contextualize results and address related issues 

## Tidy data and data intuition 
- data structures 
  - structured data 
    - can be stored in database SQL 
    - tables with rows and columns 
    - requires a relational key (used to ID any record or row of data from a table; can ID relationships between tables) 
  - semi strucured data 
    - not in relational database
    - has organizational properties (easier to analyze) 
    - CSV, XML, JSON 
  - unstructured data 
    - non tablular data (80% of the world) 
    - images, text, audio 
 - *data will not be in "ready to analyze" form*
 - Semi strucutre data 
  - CSV file; each column is separated by a comma 
  - row is sepaarted by a new line 
  ".csv" extension -- can be translated into google sheet 
  - JSON (javascript object notation) 
    - intuitive 
    - key value pairs 
      - {"KEY":"VALUE"}
    - can be nested within attributes 
  - XML file / extensive makrup language 
    - elements have opening and closing tags 
    - can store and transmit restructure arbitrary data 
> relaional database: set of interdependent tables 
  - info is stores across tables 
  - can help connect info between data tables 
> unstructured data: record info about the state of the world (text files and documents, social media data, email data, websites and application) 

- text sentiment analysis: % of pos, neg, and neutral responses (?) 
- python: beautifulsoup web scraping 

- Tiday Data 
  - data wrangling helping untidy data, go to tidy data 
  - 1. each variable should be in a single column 
  - 2. each observation should be in a single row (?) 
  - 3. there should be one table for each type of data 
  - 4. mult. tables --> should inc column (?) 
  - tidy data == rectangular data 
  - tidy data allows data sets to be combined 
  - dont let columns combine 2 diff. variables 
  - we go from books to datasets with tidydata set and data wrangling 
  - tidy dataset helps produce graphical results (nice looking ones) 
    - quicker you get data in useful form, the quicker you can get to the actual science or analysis of a data 
- Data intuition (?) 
   - theory vs practice: tai's model 
   - extracting value from data (data under the curve?) 
   - fermi estimation (back of the envelope; and approximate estimations) 
    - a rough calculation to arrive at a reasonable estimate unknowns and all where the result could be considered logically approximate 
    - the steps that lead to a logical approximation 
    - all it matters is getting in the right ball park 
    - number of digits (can round # to nearest order of magnitude) 
    - depending how "back of you envelope" you make your caluclation, they can orient you/help you on the type of estimations you can make
    - can estimate shape, peak, etc. (you see certain things evolve in the data) 
    > In data intuition 
      - think about questions and expectations 
      - do some fermi calculations (back of env calcs) 
      - write code and look at outputs (think about those outputs) 
      - use gut instrinct/backgorund knowledge to guide (whats yer gut tellin ya) 
      - review code and fix bugs 
      - create test cases - "sanity checks" 
   
