# ArmstrongNumber
Program to find the Armstrong number or not.

Explanation:
=============
The program starts with the declaration of the package org.javainterview.

Next, the AmstrongNum class is defined. This class contains the logic to determine whether a given number is an Armstrong number.

The AmstrongNum class has a private method called num(). This method is responsible for taking input from the user, performing the Armstrong number check, and displaying the result.

Within the num() method, a Scanner object named scan is created to read input from the user.

The program prompts the user to enter a number by displaying the message "Enter the Number: ".

The entered number is read using the nextInt() method of the Scanner class and stored in the num variable of type int.

Three additional variables are declared: r, sum, and temp. r is used to store the remainder, sum keeps track of the sum of the cubes of the digits, and the temp is a temporary variable to store the original number for later use.

A while loop is used to iterate as long as the temp is greater than 0.

Inside the loop, the remainder of temp divided by 10 is stored in the variable r.

The cube of r is added to the sum variable.

temp is divided by 10, effectively removing the rightmost digit from temp for the next iteration.

After the loop finishes, the program checks whether the sum is equal to the original number num. If they are equal, it means that num is an Armstrong number. In this case, the program displays the message "It's an Armstrong number.".

If the sum is not equal to num, it means that num is not an Armstrong number. The program displays the message "It's not an Armstrong number.".

The main method is declared, which is the entry point of the program.

Inside the main method, an instance of the AmstrongNum class is created using the statement AmstrongNum info = new AmstrongNum();.

The num() method is called on the info object to start the Armstrong number check process.

The program execution ends.

==> In summary, this program prompts the user to enter a number, checks whether the number is an Armstrong number or not, and displays the result accordingly. An Armstrong number is a number where the sum of the cubes of its digits is equal to the original number. <==
