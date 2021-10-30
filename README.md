# 66DaysOfData
Documenting my journey on 66 days of data


Haha, first off, it looks like my initial write up of what I'm working on disappeared. 🤦
I'll have to fix that in the next couple of days or find out where it went.

# Day 2:
Today I set up the Jupiter Notebooks and Anaconda. Feels like there are a million different programs that exist within the computer world just for working with computers and that is kind of overwhelming. I'll make more progress on Day 3.

# Day 3:
I learned about virtual environments and how to use the Anaconda Terminal!

# Day 4:
A few minutes in the Python Crash Course

# Day 5:
Big takeaways on Python Crash Course
You can use the {} to make writing out saved variable data much easier. Example:
num = 23
name = Dude
print("Your name is {} and you ate {} hot dogs.".format(name,num))

That will print out "Your name is Dude and you ate 23 hot dogs."

You can use multiple [] to call a list nested within a list.
list = [1, 2, [3, 4]]
list[2][1] would be the 4 inside of that list

Quick reminders:
list = []
Can append stuff to them or call out values or rewrite values

tupples = ()
Immutable = cannot change any values set in them

dictionary = {'key':'value'}
Need to map a key to a value (just like input to output in math). They are always key value pairs.

set = {}
These will only contain unique values so they eliminate any repeating values. (Not useful in data where you probably want to keep repeating values). These are each one value usually unlike a dictionary which maps one key to one value.

List comprehension:
I've struggled with this in the past. The goal of using it is to skip extra for loops and using the append function. Just make the new list in one line of code.
Grab everything in the first line (the for loop) and paste it at the end of a line in brackets.
Grab whatever you want to append and put it in the first part of the brackets before the for loop.
That should work.
