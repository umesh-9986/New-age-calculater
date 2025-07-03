from datetime import date

# Ask user for birth year
name = input("Enter your name: ")
birth_year = int(input("Enter your birth year (YYYY): "))

# Get current year
current_year = date.today().year

# Calculate age
age = current_year - birth_year

print(f"Hello {name}, you are {age} years old in {current_year}!")# New-age-calculater
