Word Search Solver
This program allows you to search for multiple words in a word search grid. It is implemented in C++ and demonstrates strong problem-solving and coding skills.

Description
The Word Search Solver program takes a word search grid as input and prompts the user to enter the words to be searched. It uses a linked list-based data structure to represent the grid and search for the words efficiently.

The program starts by initializing the word search grid based on user input. It creates a linked list of nodes, where each node represents a character in the grid. The linked list is structured horizontally and vertically to form the grid.

After initializing the grid, the program prompts the user to enter the words to be searched. The words are stored in a vector for easy access and comparison.

The searching process begins by traversing the grid and comparing each character with the first character of the search word. If a match is found, the program recursively searches the neighboring cells to determine if the remaining characters of the search word are present. If all characters are found, the word is considered to be found in the grid.

The program repeats the searching process for each word entered by the user and displays the search results accordingly. The user can continue searching for words or choose to exit the program.

Features
Efficient word search in a word search grid
Ability to search for multiple words
User-friendly interface with prompts and search results
Easy customization and extension for different word search grids
Installation
To run the Word Search Solver program, follow these steps:

Clone the repository to your local machine.
Compile the code using a C++ compiler.
Run the executable file.
Follow the on-screen instructions to enter the word search grid and words to be searched.
View the search results and continue searching as desired.
Usage
Upon running the program, you will be prompted to enter the number of words to be searched.
Enter the word search grid by providing the characters row by row.
Enter the words to be searched one by one.
The program will display the search results for each word entered.
To search for additional words, enter them when prompted.
To exit the program, enter "quit" when prompted.
Requirements
C++ compiler
Standard C++ library
