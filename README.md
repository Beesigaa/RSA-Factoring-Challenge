###RSA Factoring Challenge
From Wikipedia: RSA (Rivest–Shamir–Adleman) is a public-key cryptosystem, one of the oldest widely used for secure data transmission. The initialism "RSA" comes from the surnames of Ron Rivest, Adi Shamir and Leonard Adleman, who publicly described the algorithm in 1977. An equivalent system was developed secretly in 1973 at Government Communications Headquarters (GCHQ), the British signals intelligence agency, by the English mathematician Clifford Cocks. That system was declassified in 1997

##Background
We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.

This project is NOT mandatory at all. It is 100% optional. Doing any part of this project will add a project grade of over 100% to your average. Your score won’t get hurt if you don’t do it, but if your current average is greater than your score on this project, your average might go down. Have fun!
0.0. Factorize all the things!
#advanced
Factorize as many numbers as possible into a product of two smaller numbers.

Usage: factors <file>
where <file> is a file containing natural numbers to factor.
One number per line
You can assume that all lines will be valid natural numbers greater than 1
You can assume that there will be no empy line, and no space before and after the valid number
The file will always end with a new line
Output format: n=p*q
one factorization per line
p and q don’t have to be prime numbers
See example
You can work on the numbers of the file in the order of your choice
Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on
Time limit: Your program will be killed after 5 seconds if it hasn’t finish
Push all your scripts, source code, etc… to your repository
we will only run your executable factors

1. RSA Factoring Challenge
#advanced
RSA Laboratories states that: for each RSA number n, there exist prime numbers p and q such that

n = p × q. The problem is to find these two primes, given only n.

This task is the same as task 0, except:

p and q are always prime numbers
There is only one number in the files
How far can you go in less than 5 seconds?

Read: RSA Factoring Challenge
