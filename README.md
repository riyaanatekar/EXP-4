riya ravi natekar
25070123093

AIM
To study and understand the concept of sets in Python, including creation, modification, and common set operations such as union, intersection, difference, and symmetric difference.

THEORY
Sets in Python are an unordered collection of unique elements. A set:
Automatically removes duplicate values.
Does not support indexing or slicing since it is unordered.
Allows mathematical set operations like union, intersection, difference, and symmetric difference.

Key Characteristics:
Creation of Sets:
Sets are defined using curly braces {} with elements separated by commas.
Uniqueness:
If duplicate elements are added, they are automatically removed.
Adding/Removing Elements:
Use .add() to add a new element.
Use .remove() to delete an element.
Set Operations:
Union (|): Combines all elements from two sets.
Intersection (&): Elements common to both sets.
Difference (-): Elements in one set but not in the other.
Symmetric Difference (^): Elements in either set but not both.
Immutable Sets:
A frozenset is an immutable version of a set — you can’t add or remove elements once it’s created.
Example Uses:
Sets are useful when you need to store unique data, perform membership testing, or compare datasets mathematically.

ALGORITHM
 PROGRAMS WITH ALGORITHMS

 Program 1: Unique Event Participants
 Aim
To remove duplicate student registrations using sets.
Algorithm
Start
Create a list of participant names with duplicates
Convert the list into a set
Print the unique participant names
Stop
Program 2: Common Elective Subjects
 Aim
To find the subjects chosen commonly by all students using intersection.

Algorithm
Start
Create three sets of subjects for student1, student2, student3
Apply intersection operation
Store result in common_subjects
Print common subjects
Stop
 Program 3: Cricket and Football Club Students
 Aim
To find students in both clubs and only one club.
Algorithm
Start
Create a set for cricket club students
Create a set for football club students
Find students in both clubs using intersection
Find students only in cricket using difference
Find students only in football using difference
Display results
Stop
Program 4: Absent Students List
 Aim
To find absent students using difference operation.
Algorithm
Start
Create a set of total students
Create a set of present students
Subtract present from total set
Store result in absent set
Print absent students
Stop
 Program 5: Remove Invalid Course Codes
 Aim
To remove discontinued course codes from a set using remove/discard.
Algorithm
Start
Create a set of valid course codes
Remove discontinued code using discard
Remove another code using remove
Print updated set
Stop


CONCLUSION
The experiment successfully demonstrated how Python sets work. You learned how to:
Create and print sets.
Understand that sets do not allow duplicates.
Add and remove elements.
Perform basic set operations like union, intersection, difference, and symmetric difference.
Use frozenset where immutability is required.
Thus, the aim was achieved — you now understand the functionality and importance of sets in Python, along with their core operations and characteristics.
