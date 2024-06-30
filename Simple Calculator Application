Import math

# Function to perform basic arithmetic operations
Def calculate(operator, num1, num2):
If operator == ‘+’:
Return num1 + num2
Elif operator == ‘-‘:
Return num1 – num2
Elif operator == ‘*’:
Return num1 * num2
Elif operator == ‘/’:
If num2 == 0:
Return “Error: Division by zero”
Else:
Return num1 / num2
Elif operator == ‘**’:
Return num1 ** num2
Elif operator == ‘sqrt’:
If num1 < 0:
Return “Error: Square root of negative number”
Else:
Return math.sqrt(num1)
Else:
Return “Error: Invalid operator”

# Function to handle user input and display result
Def main():
Print(“Welcome to Simple Python Calculator!”)
Print(“Operations supported: +, -, *, /, ** (exponentiation), sqrt (square root)”)
Print(“Enter ‘quit’ to exit the calculator.”)

While True:
Expression = input(“Enter an expression (e.g., 5 + 3): “)

If expression.lower() == ‘quit’:
Print(“Exiting calculator...”)
Break

Try:
Parts = expression.split()
If len(parts) != 3:
Raise ValueError(“Invalid input format”)

Num1 = float(parts[0])
Operator = parts[1]
Num2 = float(parts[2])

Result = calculate(operator, num1, num2)
Print(f”Result: {result}”)

Except ValueError as ve:
Print(f”Error: {ve}”)
Except Exception as e:
Print(f”Error: {e}”)

Print() # Print an empty line for readability

If __name__ == “__main__”:
main()
