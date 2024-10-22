# FizzBuzz2024
max_count = int(input("数いくつまで数えるか: "))

for i in range(1, max_count + 1):
    if i % 15 == 0:
        print("FizzBuzz")
    elif i % 3 == 0:
        print("Fizz")
    elif i % 5 == 0:
        print("Buzz")
    else:
        print(i)
