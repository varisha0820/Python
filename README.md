# Python
Programming in Python
Write python program to print first letter of your name 
a) Example: Peter
               *      *
               *             *
               *              *
               *      *
               *
               *
               *
b) Print your name by using for loop

c) check the user name is palindrome or not



ANSWERS 
a) write python program to print first letter of your name
    for row in range(4) :
    for col in range(7) :
        if (row-col==0) or (row+col==6) :
            print("*",end="")
        else :
            print(end=" ")
    print()

b)  print your name by using for loop 
name="Varisha"
for letters in name :
    print(letters)

c) check the user name is palindrome or not 
def palindrome(word):
    x=word.replace(" ","")
    return x==x[::1]
username= input("varisha vardhan:-")
if palindrome(username):
    print(f"{username}is a palindrome.")
else:
    print(f"{username}is not a palindrome.") 
