# Get_Next_Line

This project is about programming a function that returns a line read from a file descriptor.
This will make you learn a highly interesting new concept in C programming: static variables.

# Testing

You only have to edit the get_next_line.c file and uncomment the main function and headers inside it. You can edit test.txt files to put another text if you wish to test othe cases. Then simply run this command (change "xx" with desired buffer size) :

gcc -Wall -Werror -Wextra -D BUFFER_SIZE=xx get_next_line.c get_next_line_utils.c && ./a.out

Or you can also use this third party tester to fully test the project

https://github.com/Tripouille/gnlTester
