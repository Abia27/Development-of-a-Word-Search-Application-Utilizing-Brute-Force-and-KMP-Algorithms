# Development-of-a-Word-Search-Application-Utilizing-Brute-Force-and-KMP-Algorithms
## Functional Requirements
### 1. Search Functionality:
• The application must facilitate the user’s ability to input a search term and initiate a search across multiple
text files.
• The program should accurately locate and return the following details for each occurrence of the search term:
– Name of the file
– Row number
– Column number (position within the row)
### 2. Advanced Matching Options: 
The program must include a set of advanced matching options to enhance the
flexibility and usability of the search functionality:
• Whole Word Match:
– Unchecked Option: The application should return all instances of the search term, including substrings
within larger words. For example, searching for ”pak” should yield results such as ”Pakistan”, ”adampak”,
”abnopakis”, and ”pak”.
– Checked Option: The application should restrict results to exact matches of the search term, ensuring
that only whole words are returned. For example, searching for ”pak” should return only ”pak”.
• Case Sensitivity:
– Unchecked Option: The application should be case-insensitive, meaning that variations in the upper and
lower case should not affect the search results. For example, a search for ”bilal” should return ”Bilal”,
”bilaL”, and ”bIlaL”.
– Checked Option: The application should be case-sensitive, returning results that match the case of the
search term exactly. For example, searching for ”bilal” should yield only ”bilal”, while ”BilaL” should be
returned for ”BilaL”.
### 3. Performance Evaluation:
• The application must implement both the Brute Force and KMP algorithms to perform the word search.
• Upon completion of each search, the application should record and display the time taken by each algorithm
to process the search.

## Non-Functional Requirements
### 1. User Interface:
The application should feature an intuitive and user-friendly GUI, allowing users to easily input
search terms and view results. It should include clear labelling for options and results to enhance usability.
### 2. Robustness and Error Handling: 
The program should include error handling to manage scenarios such as:
• Invalid file formats
• Empty search inputs
• Files that do not contain the search term
5. Performance Evaluation:
• The application must implement both the Brute Force and KMP algorithms to perform the word search.
• Upon completion of each search, the application should record and display the time taken by each algorithm
