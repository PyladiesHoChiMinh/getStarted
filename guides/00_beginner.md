# What is programming? And why is Python easy?

Programming in different contexts may involve doing very different things. For example:

* In data science, it involves transforming data (from mixed-type tables to numerical matrices, interpolate missing values, normalize ambiguous values, etc.) and integrating data processing tools most of the time.
* In software engineering, it involves combining existing software to new systems most of the time.
* In learning, it involves solving logical puzzles most of the time.

Learning to program only gives you an understanding of the process of solving a problem using the computation power of a computer, and the most basic building blocks to combine into a solution. It takes time to efficiently use said process (by efficiently I mean to solve a problem and only cry and curse a couple of times a day). As you progress, you will discover more building blocks to use, then getting overwhelmed & depressed when you realize how much you have to learn, but finally feel proud to call yourself a software engineer or data scientist, or even simply a programmer.

It is a long road, there will be many times you feel programming work is not for you. In those times, try doing something else to realize how well this career pays, how good most working environments in this career are, and how many jobs are available for you to pick.

I hope I successfully amused you a little bit before going into all the boring stuffs below. Without further ado, let's get started.

## Example: Prime number detector

For people who is new to programming:

Programming is simply structuring simple instructions into complex procedures for the computer. While there will be many basic instructions to learn, only 3 rules to structure them is ever needed. This simple program will introduce to us the three rules:

```
let is_prime(n) be a procedure to determine whether a number n is a prime number or not:
    first, let there be a number i
    second, let i be 2

    while i < n:
        if remainder of n / i is not equal to 0:
            let increase i by 1 (i = i + 1)
        else:
            return False

    return True
```
3 rules:
 * First (do this) then (do that)
 * If (condition is met) then (do sth) else (do sth else)
 * While (condition is met), (do sth)

You can think of any combination using these 3. That's all programming is all about: Structuring existing actions into new actions that tell the computer what you want it to do.

## Prime detector in Python:

The first benefit of Python mentioned in the [welcoming text](../README.md): "Python is probably the easiest language to learn" is because its "words" are uncomplicated and very close to normal English:

```
def is_prime(n):
    i = 2

    while i < n:
        if n mod i != 0:
            i = i + 1
        else:
            return False
            
    return True

```

Hopefully, I successfully put a sense of "what is programming" into your mind. We will actually explore more about programming with Python in the next guides.
