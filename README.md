Coded by n1c0t1n3

AD! (Add Data!) for MySQL


<-- What is this? -->

AD! is a program that will generate code for entering data into a MySQL Table. The program will create a code based on name.txt and your input(type). The output looks like:

ADT:
INSERT INTO TestTable (Data, Type) VALUES ('Data1', 'What extension I want'); 
INSERT INTO TestTable (Data, Type) VALUES ('Data2', 'What extension I want'); 

ADG: 
INSERT INTO TestTable (Data, Type, Cloud) VALUES ('Data1', 'What extension I want', 'Cloud');
INSERT INTO TestTable (Data, Type, Cloud) VALUES ('Data2', 'What extension I want', 'Cloud');


<-- How to use -->

Linux: python AD.pyc
Windows: In CMD: python AD.pyc or double click on AD.pyc
MacOS: python AD.pyc


<-- Dependences -->

Python3, Pyfiglet


