# Food Price Analysis

## Overview
Food Price Analysis is a project designed to analyze and extract relevant information from HTML files related to food products. The project comprises several modules, each tailored to perform specific tasks such as data validation, page ranking, HTML parsing, inverted indexing, web crawling, finding patterns using regular expressions, frequency counting, and search frequency analysis.

## Modules
### 1. Data Validation
- Purpose: Validates the title and language of HTML files.
- Algorithms: File Reading Algorithm, Folder Listing Algorithm, Data Validation Algorithm, Main Method Algorithm.

### 2. Page Ranking
- Purpose: Ranks files based on word frequencies.
- Algorithms: Word Frequency Count Algorithm, File Reading Algorithm, Page Ranking Algorithm, Main Method Algorithm.

### 3. HTML Parsing
- Purpose: Extracts relevant information from HTML files.
- Algorithms: HTML Parsing Algorithm (using Jsoup library), Duplicate Checking Algorithm, File Writing Algorithm.

### 4. Inverted Indexing
- Purpose: Builds an inverted index for efficient word frequency retrieval.
- Data Structures: Ternary Search Trie, ArrayList, Hashtable.
- Algorithms: TST Insertion, Document Frequency Calculation, Print Frequency, Indexing.

### 5. Web Crawling
- Purpose: Extracts hyperlinks and web page content for analysis.
- Data Structures: List\<WebElement\>, List\<String\>, Hashtable\<String, String\>, File, FileWriter.
- Algorithms: findHyperLinks, writeContent, createFile.

### 6. Finding Patterns using Regular Expressions
- Purpose: Searches for specific patterns in HTML files.
- Data Structures: String, ArrayList\<String\>, File, FileInputStream, Pattern, Matcher.
- Algorithms: innerContent, fileNameList, dataValidation, main.

### 7. Frequency Count
- Purpose: Counts the frequency of specified words in HTML files.
- Data Structures: Map\<String, Integer\>, Map\<String, Map\<String, Integer\>\>, File, List\<String\>, Scanner.
- Algorithms: recurrenceOfWord, searchingFolder, getFileNameWithoutExtension, Frequency, main.

### 8. Search Frequency
- Purpose: Searches for the frequency of specified words in web pages and maintains search history.
- Data Structures: HashMap\<String, Integer\>, String, StringBuilder, BufferedReader, String\[\], Scanner.
- Algorithms: SearchCount, main.

## Installation

To use this project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/smitrami-123/Food_Price_Analysis.git
   ```
2. Import the project into your preferred Java IDE.

## Usage

1. Open the project in your Java IDE.
2. Run the main class to start the food price analysis.

## Contributors
- [Smit Rami](https://github.com/smitrami-123)

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
