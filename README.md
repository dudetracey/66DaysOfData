# 66DaysOfData
Documenting my journey on 66 days of data


Haha, first off, it looks like my initial write up of what I'm working on disappeared. 🤦
I'll have to fix that in the next couple of days or find out where it went.

## Day 2:
Today I set up the Jupiter Notebooks and Anaconda. Feels like there are a million different programs that exist within the computer world just for working with computers and that is kind of overwhelming. I'll make more progress on Day 3.

## Day 3:
I learned about virtual environments and how to use the Anaconda Terminal!

## Day 4:
A few minutes in the Python Crash Course

## Day 5:
Big takeaways on Python Crash Course
### You can use the {} to make writing out saved variable data much easier. Example:
num = 23
name = Dude
print("Your name is {} and you ate {} hot dogs.".format(name,num))

That will print out "Your name is Dude and you ate 23 hot dogs."

### You can use multiple [] to call a list nested within a list.
list = [1, 2, [3, 4]]
list[2][1] would be the 4 inside of that list

### Quick reminders and differences:
list = []
Can append stuff to them or call out values or rewrite values

tupples = ()
Immutable = cannot change any values set in them

dictionary = {'key':'value'}
Need to map a key to a value (just like input to output in math). They are always key value pairs.

set = {}
These will only contain unique values so they eliminate any repeating values. (Not useful in data where you probably want to keep repeating values). These are each one value usually unlike a dictionary which maps one key to one value.

### List comprehension:
I've struggled with this in the past. The goal of using it is to skip extra for loops and using the append function. Just make the new list in one line of code.
Grab everything in the first line (the for loop) and paste it at the end of a line in brackets.
Grab whatever you want to append and put it in the first part of the brackets before the for loop.
That should work.

## Day 6
Continuing Python basics.
### Functions: I have been confused in previous coding on how to set up the initial def line.
Examples:
def my_func(name):
  print('Hello '+name)
my_func('Jose')
(Runs to give you "Hello Jose")
*Default value*
def my_func(name='Default Name'):
  print('Hello '+name)
 my_func('Jose')
 (Runs "Hello Jose" or else if there was no Jose then it would say "Hello Default Name")
 
 ### When do you use return?
 If you need to store a new value (for example, a function that squares the input) and then use that value or print it later, then you will return. If all you need to do is print something without storing it, then you don't need return.
 
 ### Documentation: During a function, you can use """ to block off comments about the function and describe what it is doing. It can include multiple lines"""
 Use shift+tab to find out what the documentation string is. Can be done to the functions I build or to other functions inside the base of python. (Like range function in python then shift+tab)
 
 ### Lambda expressions:
 They are used when you want to do a function one time and don't really need to spend lines defining a function you barely use. Example:
 You want to take a list and multiple all the elements in it by 3
 seq = [1,2,3,4,5]
 list(map(lambda num: num\*3, seq))
 The output here would be the list [3, 6, 9, 12, 15]
