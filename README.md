# modified-phone-directory
My solution for Chapter 11 Exercise 5 of “Introduction to Programming Using Java”.
Implementation notes: edited the PhoneDirectoryFileDemo.java class provided by the 
textbook's author, allowing it to read and write XML files.

Problem Description:
The sample program PhoneDirectoryFileDemo.java, from Subsection 11.3.2, stores
name/number pairs for a simple phone book in a text file in the user’s home directory.
Modify that program so that it uses an XML format for the data. The only significant
changes that you will have to make are to the parts of the program that read and write
the data file. Use the DOM to read the data, as discussed in Subsection 11.5.2. You can
use the XML format illustrated in the following sample phone directory file:
<?xml version="1.0"?>
<phone directory>
<entry name=’barney’ number=’890-1203’/>
<entry name=’fred’ number=’555-9923’/>
</phone directory>
(This is just a short exercise in basic XML processing; as before, the program in this
exercise is not meant to be a useful phone directory program.)
