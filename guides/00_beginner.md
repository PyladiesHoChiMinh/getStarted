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

Python is probably the easiest language to learn because its "words" are uncomplicated and very close to normal English:

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

Hopefully, I have successfully provide the essense of "what is programming" here. We will actually explore more about programming with Python in the next guides.
