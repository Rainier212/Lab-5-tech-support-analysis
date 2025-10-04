TechSupport - the DodgySoft Technical support system.

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

This project is discussed in chapter 6.


This project implements a technical support system for customers of the 
DodgySoft software company. Users can describe their software problems and 
get advice instantly!

The idea is based on Eliza - a famous program described by Joseph Weizenbaum 
in 1966. (Do a web search for "Eliza" and "Weizenbaum" if you want to know 
more about this.)

In fact, it is much more primitive than Eliza. But that's enough to match the 
quality of many software companies' technical support advice...  ;-)

To start this program, create a SupportSystem object and execute the "start" 
method.

Then start describing your problem by typing in the terminal window.

The purpose of this project is to demonstrate and study library classes, such 
as ArrayList, HashMap, HashSet, and Random.

ANSWERS TO QUESTIONS

43. It adds a value to key if and ONLY if the key is not already there.


46. When I generated documentation for the project, this is what it showed me:

InputReader: InputReader reads typed text input from the standard text terminal.
Responder: The responder class represents a response generator object.
SupportSystem :This class implements a technical support system.
WordCounter :Keep a record of how many times each word was entered by users.

It showed me the different classes and their descriptions.


47. @author  Michael Kölling and David J. Barnes
    @version Tells us the version of the document
    @param input A set of words entered by the user.
    @return  A set of Strings, where each String is one of the words typed by the user
    @param words  A set of words entered by the user
    @return       A string that should be displayed as the response


48. Here are some other Javadoc key symbols + their descriptions: 
	@author - Specifies the author
	@deprecated - Adds a comment indicating that this API should no longer be used
	{@code  text} - Displays text in code font without interpreting the text as HTML markup 
	{@docRoot} - Represents the relative path to the generated document's (destination) root directory from any generated page.
	@return - Adds a "Returns" section with the description text.
	@see - Adds a link, with visible text label
	
	
49. InputReader
    Responder
    SupportSystem
    WordCounter
