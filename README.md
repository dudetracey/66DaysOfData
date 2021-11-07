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

## Day 7
Spent 10 minutes reviewing methods

## Day 8
Today I completed the first set of exercises for the course. I made a few syntax errors, but mainly I got through them easily. 
One question I am leaving for the next day is to figure out how 'pass' can be used in the final problem, which asked me to build a function that utilizes a lot of if/elif/else statements.

## Day 9
I spent an hour today going over the Python crash course answers, then jumped straight into Numpy.
Big takeaway from the answers on Python exercises: I still love to make too many variables and shift to a new variable each time I do a method or change data in some way. I imagine that is a natural part of programming is you become more efficient so the functions that take me six lines now will eventually only take one or two lines.
Numpy: so many cool ways to make data similar to what I learned in college linear algebra. The most fun I had learning all day (and I'm in my first week of a new job right now). I jumped straight into the exercises so I could practice the basic syntax right away with the types of random, the types of arrays you can make, and made lots of silly beginner errors along the way. Super fun hour overall.

## Day 10
Not much time spent, less than 20 min on Numpy array indexing. Will probably need to rewatch some of the notes in order to put them into practice.
Key takeaway: updating one version of an array will update the original array. Need to use the copy method to make a separate array that won't be updated when you update one version of an array.

## Day 11
Super short time today, learned the two ways to pull a single entry from a matrix with either [][] or [,]. Remember that we always start counting index positions from zero!

## Day 12
Another short study day. I learned about boolean arrays as a means of creating an array with certain values. I'm very curious to see why and how this is used in a future day of studying.

## Day 13
Another short day. Started numpy operations.
