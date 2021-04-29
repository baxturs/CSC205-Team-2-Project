# CSC205-Team-2-Project
Final Project
COURSE PROJECT IS 20% OF THE COURSE GRADE

In this project, you will create a system to manage the information about the inhabitants of a county.

The county has provided a file containing the details of the inhabitants.

Read the details of the inhabitants from the file into the given 'person' struct (at least 20 persons).

struct person{ // define the UDT

string pName;
long pSSN; 

char gender; 
string DOB;

float height; 
float weight;

long fSSN;
long mSSN;


person* next;
};

Create linked person-nodes. Sort the linked person-nodes in increasing order of SSN.

Provide the user the following menu items:

Display the persons (always in ascending order of SSN)

Whenever persons are displayed, all the details of the person have to appear on one line of output.

Prompt for removing a person (input SSN):

Remove the specified person-node. Sort the new list by SSN increasing and display the persons.

Prompt for adding a person:
Add a new person-node to the list (user provides the person data).

Sort the new list by SSN increasing and display the persons.

Add new people to the list in bulk by reading a supplementary file containing person data (at least 5 persons).
Create multiple new person-nodes as required.

Sort the new list by SSN increasing and display the persons.

Edit a person (user specifies one SSN and enters new details of pname, height and weight for that SSN).
Display the single person before and after editing the data.

Display all persons eligible for social security (age 65 and older)

In increasing order of age.

Display all persons at high risk of cardiovascular disease (BMI 27 and higher)

In decreasing order of BMI.

Display the male:female ratio of the population of the county (females per thousand males)

Find the parents of a person (user supplies SSN of the person).

Display mother first, then father.

Find all children of a person (user supplies SSN of the person).

In decreasing order of age (oldest first).

Find all siblings of a person (user supplies SSN of the person).

In decreasing order of age (oldest first).

(HINT: Find the parents of the person, then find all the children of each parent.)

Find all uncles, aunts, cousins, nephews and nieces of a person (user supplies SSN of the person).

Group by generation, oldest first; display by age, oldest first.

(HINT: Find the parents of the person, then find all the siblings of each parent, then find the children of each sibling.)

Develop a console application in C++ that meets the above requirements. Upload it to your GitHub repository. Submit your code as a Word file.

We will review your work on Zoom during regular class hours on Thursday 29th Apr, Tuesday 4th May, Thursday 6th May. The reviews will count towards the project grade and are worth a 40 + 30 + 30 points (in addition to the project grade of 200 points). PLEASE BE READY ON 5th May WITH YOUR COMPLETED PROJECT.

Also complete the Practical Exposure document before class on 5th May. This is a separate link in Canvas and is worth its own 100 points.

Points will be awarded as follows: Menu items 1 to 8: 10 points each (80 points)

Menu items 9, 10: 20 points each (40 points)

Menu items 11, 12: 40 points each (80 points)

Total: 200 points

Your application must include at least one file, one function, one struct, one pointer, one array and one header file. Each one that is missing in your application will cost 5 points. SUBMIT YOUR CODE AS A WORD FILE.
