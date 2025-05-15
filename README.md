# python-conditional-statements-
"Write a program to check whether the person is eligible to vote or not"
person=int(input("enter the person age:"))
limit=18
if person>=18:
    print("the person is eligible to vote")

#checking the number is even or not
'''print whether the number is even and skip the condition if not'''
num=int(input("enter the number"))
if num%2==0: print(num, "is a even number")
print("after the EXIT!!!")

#checking the number is odd or not
'''print whether the number is even and skip the condition if not'''
num=int(input("enter the number"))
if num%1==0: print(num, "is a odd number")
print("after the EXIT!!!")


'''program to determine the character enterd by a user ,whether it is an alphabet,digit or space by using seperate if condition and predefined string function'''
char=input("press any key:")
if char.isalpha():
    print("The user has entered character")
    if char.isdigit():
        print("The user has entered digit")
        if char.isspace():
            print("The user has enterd space")


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




