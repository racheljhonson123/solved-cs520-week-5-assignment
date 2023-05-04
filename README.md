Download Link: https://assignmentchef.com/product/solved-cs520-week-5-assignment
<br>
You are strongly encouraged to add comments throughout the program. Doing so will help your facilitator to understand your programming logic and grade you more accurately.

• You must work on your assignments individually. You are not allowed to copy the answers from the others. However, you are encouraged to discuss the approaches to the homework assignments with your section mates and the facilitator in your section via the discussion board.

• Each assignment has a strict deadline. However, you are still allowed to submit your assignment within 2 days after the deadline with a penalty. 15% of the credit will be deducted unless you made previous arrangements with your facilitator and professor. Assignments submitted 2 days after the deadline will not be graded.

• When the term lastName is referenced in an assignment, please replace it with your last name. You are strongly encouraged to add comments into your program! Create a new Java Project in Eclipse named HW5_lastName and complete the following requirements. Create a package named cs520.hw5. Using this package, create the following classes.

1.Create a class named Senator as follows. (This is the same class used in Assignment3). a.The instance (or member) private variables – name, party, state (String), and yearsInOffice (integer). b.A single constructor with name as its argument. c. The public get and set methods for the instance variables. d.Override the toString method to return the string representation of this object in the format “ () from has been the senator for years”.

2. Create a SenatorTest class to test the following functionality in its main method.

a. Declare and initialize an empty Queue of Senator objects named senatorQueue.

b. Declare and initialize an empty HashMap named senatorMap. The keys will be the names of the senators and the entries in the map will be the corresponding senator objects.

c.Use the BufferedReader class to read the data.txt file. The contents of the file are shown below. Create the data.txt file in HW5_lastName.

d. Read the contents of the text file one line at a time using a loop. The program should work for any number of input lines. In this loop,

1. Invoke the processInputData method for each line read. This method returns the corresponding Senator object.

2. Add this Senator object to the senatorQueue.

3. Insert this Senator object into the senatorMap using the senator’s name as the key. e. After the loop is processed, do the following.

1. Iterate over the senatorQueue and display each element to the console.

2. Access the keys of the senatorMap and assign them to an appropriate variable. Create an iterator over the keys. Iterate over each key in this set and display the associated object in the map to the console. Write a private method processInputData with return type Senator which processes its string input argument and returns the corresponding Senator object as follows.

1. Tokenize the string argument using the StringTokenizer class using the comma as the delimiter, or using the String split method.

2. Extract the name token. Create a Senator object and assign to the local variable currentSenator.

3. Read the rest of the tokens one token at a time. Use the corresponding set method on the currentSenator object to set the instance value.

4. If the yearsInOffice is not a valid number, i.e., throws an exception when parsed, set the value as -99 in the exception handling part.

5. The method should return the currentSenator object. Sample Input data.txt file: Al Franken,8,Democrat,Minnesota Amy Klobuchar,10,Democrat,Minnesota Angus King,4,Independent,Maine Ben Cardin,10,Democrat,Maryland Ben Sasse,2,Republican,Nebraska Bernie Sanders,10,Independent,Vermont Submission: Create an archive of your Eclipse project using the following steps. Select the HW5_lastName project in the Eclipse IDE’s Package Explorer or the Navigator window. Click File-&gt;Export. Select the General-&gt;Archive File option. Click Next. Specify the “To archive file:” entry as say, C:TempHW5_lastName.zip. The zip file will be created and stored in the C:Temp folder. Submit this zip file as an attachment in the Assignment Section.