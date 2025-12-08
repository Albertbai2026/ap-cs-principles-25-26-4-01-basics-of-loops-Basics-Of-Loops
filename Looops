#All questions must use a loop for full points.
from turtledemo.penrose import start



def oddnumbers(n:int) ->str:
    """
    Print out all odd numbers from 1 to n(inclusive) in a single string seperated by spaces.
    example oddNumbers(5) -> "1 3 5"
    example oddNumbers(8) -> "1 3 5 7"
    example oddNumbers(-8) -> ""
    """
def oddnumbers(n: int) -> str:
    if n < 1:
        return ""
    parts = []
    i = 1
    while i <= n:
        if i % 2 == 1:
            parts.append(str(i))
        i += 1
    return " ".join(parts)

def backwards(n)-> int:
    """
    modify the below function such that it prints out all the numbers from n to 1
    inclusive starting at n and counting down to 1
    example backwards(5) -> "5 4 3 2 1"
    example backwards(8) -> "8 7 6 5 4 3 2 1"
    example backwards(-2) -> ""
    """
def backwards(n: int) -> str:
    if n < 1:
        return ""
    parts = []
    i = n
    while i >= 1:
        parts.append(str(i))
        i -= 1
    return " ".join(parts)

def randomRepeating():
    """
    Print out a random number from 1-10 until you get a 10. Then print out how many
    times it took to roll a 10
    NOTE: Given randomness no test for this question
    :return:
    """
def randomRepeating() -> int:
    """Roll 1-10 until you get a 10. Print and return number of tries."""
    count = 0
    while True:
        count += 1
        number = randomRange(1, 10)
        if number == 10:
            print(f"It took {count} tries to get a 10")
            return count

def randomRange(n: int)
    """
    Roll random integers from 1 to 100 exactly n times.
    Print and return (lowest, highest). If n <= 0 returns (None, None).
    """
    if n <= 0:
        print("No rolls were made.")
        return (None, None)
    lowest = None
    highest = None
    i = 0
    while i < n:
        val = randomRange(1, 100)
        if lowest is None or val < lowest:
            lowest = val
        if highest is None or val > highest:
            highest = val
        i += 1
    print(f"Lowest rolled: {lowest}")
    print(f"Highest rolled: {highest}")
    return (lowest, highest)

def reverse(word:str)->str:
    """
    Takes in a string as an argument and return the given string in reverse.
    example reverse("cat") -> "tac"
    example reverse("Hello") -> "olleH"
    """
def reverse(word: str) -> str:
    if word == "" or word is None:
        return ""
    chars = []
    i = len(word) - 1
    while i >= 0:
        chars.append(word[i])
        i -= 1
    return "".join(chars)

def fizzBuzzContinuous(n):
    """
    Modify the function such that it does the fizzbuzz operation on all numbers
    from 1 to n(inclusive).
    Fizz buzz is defined as
    if the number is divisble by 3 print fizz
    if the number is divisible by 5 print buzz
    if the number is divisible by both 3 and 5 print fizzbuzz
    if none of the above apply print the number.

    As with above questions add each anseer to a string and return the final string.
    :param n:
    :return:
    """
def fizzBuzzContinuous(n: int) -> str:
    if n < 1:
        return ""
    parts = []
    i = 1
    while i <= n:
        if i % 3 == 0 and i % 5 == 0:
            parts.append("fizzbuzz")
        elif i % 3 == 0:
            parts.append("fizz")
        elif i % 5 == 0:
            parts.append("buzz")
        else:
            parts.append(str(i))
        i += 1
    return " ".join(parts)

def collatz(n):
    """
    Modify this function such that it mimics the collatz conjecture starting at n
    and prints out each number.
    The collatz conjecture is that if n is an even number divide it by 2. if n is
    an odd number multiply it by 3 and add 1.
    Repeat this process until n == 1.
    :param n:
    :return:
    """
def collatz(n: int) -> str:
    if n <= 0:
        return ""
    parts = [str(n)]
    current = n
    while current != 1:
        if current % 2 == 0:
            current = current // 2
        else:
            current = current * 3 + 1
        parts.append(str(current))
    seq = " ".join(parts)
    print(seq)
    return seq

def fibonacci(n):
    """
    for the given argument n print out the first n numbers of the fibonacci
    sequence in a single string sperated by spaces.
    The fibonacci sequence is defined as a sequence that starts with 0 then 1 as
    the first two numbers. Every subsequent number is the prior two numbers added together.
    Example fibonacci(6) -> "0 1 1 2 3 5"
    Example fibonacci(10) -> "0 1 1 2 3 5 8 13 21 34"
    Example fibonacci(1) -> "0"
    :param n:
    :return:
    """
def fibonacci(n: int) -> str:
    if n <= 0:
        return ""
    if n == 1:
        return "0"
    parts = ["0", "1"]
    count = 2
    while count < n:
        a = int(parts[-2])
        b = int(parts[-1])
        parts.append(str(a + b))
        count += 1
    return " ".join(parts)

print(fibonacci(300))
