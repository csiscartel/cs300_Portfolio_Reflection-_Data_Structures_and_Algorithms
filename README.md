# ******cs300_Portfolio_Reflection-_Data_Structures_and_Algorithms******


**Portfolio Reflection -Data Structures and Algorithms**

__What was the problem you were solving in the projects for this course?__
The central problem in the class was to architect and write an advising assistant for ABCU's Computer Science department which could persistently store, organize, and display course data. The program was supposed to input a data file of courses and provide the capabilities to search for specific course details and progress, as well as print out all of the available courses in alphanumeric order. I addressed this by testing out various data structures – vector, hash table and binary search tree (BST) – and finally used BST to implement the final program such that the sorting and retrieving of data can be done efficiently.

**How did you approach the problem? Consider why data structures are important to understand.**
I started this assessment by going through data structures used for Project One and made a summary of the good and bad points (the Big O) of all these structures according to performance in runtime-execution time/memory/speed. This analysis helped identify that a BST would be best suited to the needs. Once selected, I created structured pseudocode data load, search and print routines in an optimum manageable format. For Project Two, I turned that pseudocode into non-pseudocode C++ within a single.cpp file for readability and making sense of it all in the form of clear menu flow/logic and correctly reading the CSV file into a BST.

**How did you overcome any roadblocks you encountered while going through the activities or project?**
One of our obstacles was to have possible file parsing for all course entries, which were in full forms but with some lines missing fields or having more than they should have. To get around this, I included some form/input validation along with a basic error message for misread lines. Another problem was making sure the courses would be printed in alphabetical order, this can be solved very organically using BST’s own traversal method which is in order—the data will show up sorted without there being additional sort logic. Small "test" files and incremental compilation to the rescue, this way we could have tested functionality.

**How has your work on this project expanded your approach to designing software and developing programs?**
This project further enhanced my insights into the impact that runtime performance and memory system have on SW design choices. I learned to not just write code but critically think about what data structure was best for a given problem. Designing from pseudocode also forced me to better plan before coding, which generally resulted in more elegant and less buggy code. It renewed my commitment to modular design and reuse in programming.

__How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?__
With this project, I have been focusing more on making sure my code is structured properly logical separation of functions, proper naming conventions (getting them closer to being consistent) and inline comments that give paragraphs back their meaning. Now my code is clear enough to modify in the future for such modifications as using another data structure or expanding the advising program with new features. I have also an increased sympathy for how documentation and runtime analysis keep the codebase maintainable for other developers or versions down the line.


