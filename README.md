# Assignment-OO-Programming-Sem-2-2023-Java

The offered code's main function is a text file command-line search engine. Users can use the application to look for a specific term in a group of text files, and it will return the frequency of that word in each file, ordered in descending order of frequency. Users can show a list of files and add new files to the collection using the program.
 The code contains a number of classes, such as Main, Colors, and Search. The Java Collections Framework is used by the software to sort the search results after using the Apache Lucene library to search text files.
 
a list of classes from the code, along with a description 
Main class: This is where the program begins. The user is presented with a menu, and depending on their selection, specific actions are carried out.
Class for searching: This class symbolizes a search operation. It has tools for searching through a list of files for a specific term and provides the number of times the word appears in each file.
A utility class called "Colors" contains constants for ANSI color codes. The console output is colored as a result of it.
FileManager class: This class is a representation of the program's file manager. It includes tools for displaying and adding files to lists.
Utils class: There are utility methods in this class that are utilized by other classes. It has a way to validate user input and a way to read text from files.

some optional functions that I added to the assignment are:
Assending results: The tool might have a good ranking system that places search results in order of the quality of their matches. The user can view the ranking measure if it is shown as a percentage. The user would find it simpler to determine which search results are most pertinent as a result.
Correcting misspelled search keywords: The tool might have an option to repair misspelled search phrases. The instrument would become more effective and user-friendly as a result.
Selection of the search space: The tool might let the user choose the search space, or the text files to be searched. The tool would become more flexible and adaptable as a result.

The following features are ones I might add to the code if I had more time to do so:
Users can exclude certain files or folders from the search by using file filtering. When looking through huge directories with several subfolders or files that are unrelated to the user's search, this could be helpful.
Sorting search results: At the moment, the results are shown in the order that they were discovered. I would include the option for the user to sort the results using several factors like relevance, the most recent modification date, the file type, etc.
Support for many languages: At the moment, the program assumes that all text files are in English. To enable users to search for terms in papers written in other languages, I would add support for other languages.
The user's ability to browse and access their previous search queries is known as their search history. Users that frequently use the same search keywords or need to refer back to their past search results would benefit from this since it would save them time.
User interface Improvements: I would make the user interface more user-friendly and intuitive. This can entail adding tooltips, improving error messages, and making the tool's usage instructions more explicit.
