# Square-calulator
# Program to calculate the square and cube of a number

def calculate_square(number):
    return number * number

def calculate_cube(number):
    return number * number * number

def main():
    print("Square and Cube Calculator")
    num = int(input("Enter a number: "))
    square = calculate_square(num)
    cube = calculate_cube(num)
    print(f"The square of {num} is {square}.")
    print(f"The cube of {num} is {cube}.")

# Run the program
main()

