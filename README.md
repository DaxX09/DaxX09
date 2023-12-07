1)Write a Python program to check if a number is positive, negative or zero.
positive_count=0
negative_count=0
for i in range(1,6)
    num=int(input("Enter a number:-))
    if num>0:
    positive_count+=0
    else:
    negative_count+=0
print("Positive Number",positive_count)
print("Negative Number",negative_count)

2)Write a Python program to get the Factorial number of given number.

a=int(input("Enter a number:-))
b=int(input("Enter a number:-))
print(a*b)
print(a+b)
print(a-b)

3)Write a Python program to get the Fibonacci series of given range.

4)How memory is managed in Python?

=> Python uses dynamic memory allocation which is managed by the HEAP DATA STRUCTURE.
=> Memory Heap holds the objects and other data structue that is used in programme.

5)What is the purpose continue statement in python?
=> The continue statement is used to skip the remaining code inside the loop for the
for the current statement only.
=> When the condition num==5 become true the statement gets executed.

6) Write python program that swap two number with temp variable and without temp variable.

7)Write a Python program to find whether a given number is even or odd, 
  print out an appropriate message to the user.
num=int(input("Enter a number:-"))

if num%2==0:
    print("Even Number")
else:
    print("Odd Number")

8) Write a Python program to test whether a passed letter is a vowel or not.
letter=input("Ente an alphabate:-")
A="a"
B="e"
C="i"
D="o"
E="U"
if letter==A:
    print("Its a vowel")
elif letter==B:
    print("Its a vowel")
elif letter==C:
    print("Its a vowel")
elif letter==D:
    print("Its a vowel")
elif letter==E:
    print("Its a vowel")
else:
    print("Its a constonant")

9) Write a Python program to sum of three given integers. However, if two values are equal 
   sum will be zero.

n1=int(input("Enter number 1:-"))
n2=int(input("Enter number 2:-"))
n3=int(input("Enter number 3:-"))

if n1==n2 or n1==n3 or n2==n3:
    print("sum =0")
else:
    sum=n1+n2+n3
    print("Sum = 0", sum)
    

10)Write a Python program that will return true if the two given integer values are equal 
   or their sum or difference is 5.


11)Write a python program to sum of the first n positive integers.

12)Write a Python program to calculate the length of a string.

name="Python"

print(len(name))

13) Write a Python program to count the number of characters (character frequency) in a string

count=0
name=input("Enter your name:-")

for i in name:
    count+=1
print(count)

14) What are negative indexes and why are they used?
=> Negative index is used in python to begin sclicing from the end of the string.
i.e start:stop:step
For eg. name="Python"
here,
 P    Y    T    H   O    N 
-6   -5   -4   -3  -2   -1
the above represents negative index.
print(name[-1])

15) Write a Python program to count occurrences of a substring in a string.

16)Write a Python program to count the occurrences of each word in a given sentence

17)Write a Python program to get a single string from two given strings, separated 
   by a space and swap the first two characters of each string.
s1="Python"
s2="Java"

new_s1=s1[:1]+s2[1:]
print(new_s1)

new_s2=s2[:1]+s1[1:]
print(new_s2)

18)Write a Python program to add 'ing' at the end of a given string (length should be at least 3).
   If the given string already ends with 'ing' then add 'ly' instead if the string length of the 
   given string is less than 3,leave it unchanged.


19)Write a Python program to find the first appearance of the substring 'not' and 'poor' from 
a given string, if 'not' follows the 'poor', replace the whole 'not'...'poor' substring with 'good'. 
Return the resulting string.


20)Write a Python function that takes a list of words and returns the length of the longest one.

l1=["Python","Java","Android","Hello"]

max=len(l1[0])

word=""

for i in l1:
    if len(i)>max:
        word=i
        max=len(i)
    
print("max=",max)
print("word=",word)


21)Write a Python function to reverses a string if its length is a multiple of 4.

s1=input("Enter a string:-")

if len(s1)%4==0:
    print(s1[::-1])
else:
    print(s1)

22)Write a Python program to get a string made of the first 2 and the last 2 chars from a given a string.
   If the string length is less than 2, return instead of the empty string.

s1=input("Enter a string:-")

if len(s1)<2:
    print("Empty String.")
else:
    s2=s1[::1]+s1[-2::]
    print(s2)

23) Write a Python function to insert a string in the middle of a string.

s1=input("Enter string:-")
s2=input("Enter 2nd string:-")


s3=s1[:2]+s2+s1[-2:]

print(s3)




