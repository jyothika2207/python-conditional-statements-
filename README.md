# python-conditional-statements-
"Write a program to check whether the person is eligible to vote or not"
person=int(input("enter the person age:"))
limit=18
if person>=18:
    print("the person is eligible to vote")
output:
    enter the person age: 19
the person is eligible to vote


#checking the number is even or not
'''print whether the number is even and skip the condition if not'''
num=int(input("enter the number"))
if num%2==0: print(num, "is a even number")
print("after the EXIT!!!")
output:
      enter the number 22
     22 is a even number
     after the EXIT!!!


#checking the number is odd or not
'''print whether the number is even and skip the condition if not'''
num=int(input("enter the number"))
if num%1==0: print(num, "is a odd number")
print("after the EXIT!!!")
output:
       enter the number 33
       33 is a odd number
       after the EXIT!!!



'''program to determine the character enterd by a user ,whether it is an alphabet,digit or space by using seperate if condition and predefined string function'''
char=input("press any key:")
if char.isalpha():
    print("The user has entered character")
    if char.isdigit():
        print("The user has entered digit")
        if char.isspace():
            print("The user has enterd space")
output:
        press any key: kl
        The user has entered character



#checking if else condituion statements.
person=int(input("enter the person age:"))
limit=18
if person>=18:
    print("the person is eligible to vote")
else:
    print("The person is not eligible to vote")

    '''write a program to find the smallest of two numbers by using if-else condition'''
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
if a<b:
    small=a
else:
    small=b
    print("small value is ",small)
output:
       enter the value of a: -4
       enter the value of b: -99
       small value is  -99


    '''wrie a program to enter a character (atoz),if the entered character is in lowercase convert into uppercase'''
char=input("enter any character from a-z")
if char>='A' and char<='Z':
    char=char.lower()
    print("converted case input char:",char)
else:
    char=char.upper()
    print("converted case input char:",char)
output:
       enter any character from a-z b
        converted case input char: B


        '''check whether the given input is a leap year for 4 years and centurians by if-else'''
y=int(input("enter year:"))
if y%4==0 or y%100==0 or y%400==0:
    print(y,"is a leap year")
else:
    print(y,"is not a leap year")
output:
        enter year: 2020
        2020 is a leap year
 
