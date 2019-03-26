# Sequence-Sort
using C++

# Program’s purpose:
The purpose of this program is sort a file of data as a sequence set with each field being a separate part of the record data. This then allows the user to delete, modify, or create new file data into the program. 

Our program’s job is to take in a data set, in this case a large number of United States postal addresses, take them into memory, force all of the fields into a fixed size, and then output the new data into a new outfile. The program also needs to be able to display a given record, display a specific field in a record, modify and field in a record, insert new records, and delete old records.  Additionally our program needs to verify that the sequence set is consistent, and be able to rebuild the sequence set.


# How to compile:
Make sure all files are located within the same folder, and compile/run AddressMain.cpp.  The program will then give you a list of commands that the user can implement such as:

Press A: to delete a record

Press B: to modify a field within a record

Press C: to insert a new record

Press D: to output all records to file

Press E: to display all records

Press F: to display a selected block of records

Press G: to display a single selected record

Press Q: to exit the program


The user then may or may not be prompted for a Zipcode to find a specific file or a Y/N question to make sure they hit the correct function they wanted to implement. 
