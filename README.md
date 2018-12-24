# CS111CProjectB
Interfaces
Write an interface for a list that works like this: 

entries can only be added to and removed from the beginning or end of the list
entries can be accessed in any position
entries begin at index 0
Your interface must use generics and this class header:

public interface HeadTailListInterface<T>
Note that you are only creating the interface. You are NOT implementing the methods. (You will do that in a future lab!)

Requirements

Your interface must:

compile (20 points)
contain these exact method headers with full, complete javadoc-style documentation (80 points)
void addFront(T newEntry)
void addBack(T newEntry)
T removeFront()
T removeBack()
T getEntry(int position)
void display()
int contains (T entry)
boolean isEmpty()
int size()
void clear()
Each method must use javadoc-style comments. You can review the List and Bag Interfaces files, the Oracle guide (Links to an external site.)Links to an external site., and the video from the Module 3 lectures (Links to an external site.)Links to an external site. for more information about javadoc-style comments. Make sure the documentation includes a general comment/description about the purpose of the interface. And the comments for each method should describe:

what the method does
what the parameters are (if any)
what the method returns (if anything)
what the exceptions are (if any)
I recommend running a javadoc tool to test your comments.

In Eclipse, you can right-click on the project name, then select Export, Java, Javadoc
Extra Credit (10 points)

Add three additional methods to the BagInterface interface. Make sure the new methods are consistent with the bag ADT. If you add a method that modifies the ADT in a minor way, update that part of the BagInterface to reflect your change. But make sure you keep with the "general idea" of a bag!

Submit only the method headers with full javadoc style documentation (you can submit as a .txt, .doc, .pdf, etc. file type). Do not submit the full interface- only the new methods or any documentation that you have changed.

Submission

Upload either HeadTailListInterface.java or a zip of HeadTailListInterface.java and your extra credit.

If submitting as a group, submit one assignment only through one group member's Canvas account. Put the names of all group members in Canvas comment box on the submission page.
