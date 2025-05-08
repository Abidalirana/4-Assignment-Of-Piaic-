Assignment 04: on date 8 may 2025 Python Crash Course Practice (Chapters 2 - 4)
📘 Based on Python Crash Course by Eric Matthes (Chapters 2 to 4)

✨ Part 1: Variables & Input
✅ Q1. Favorite Movie Intro
Ask the user for:

Their name
Their favorite movie
Print a sentence like: Ali’s favorite movie is Interstellar.

✅ Q2. Case Converter
Ask the user to enter a word.

Print:

The word in uppercase
The word in lowercase
The word in title case
✅ Q3. Simple Math with Input
Ask the user to input two numbers using input()

Convert them to int or float

Print:

Sum
Difference
Product
Quotient
# Sample Output:
Enter first number: 5  
Enter second number: 2  

Sum: 7  
Difference: 3  
Product: 10  
Quotient: 2.5  
📋 Part 2: Lists & Indexing
✅ Q4. My Friends List
Create a list of 4 friends’ names.
Print each name using a for loop.
✅ Q5. Update Your List
Create a list of 3 favorite fruits.
Replace the second fruit with another.
Add one fruit to the end using .append().
Add one to the beginning using .insert(0, ...).
Print the list after each change.
✅ Q6. List Length Reporter
Ask the user to enter 5 favorite animals (use input()).

Store each animal in a list.

After collecting:

Print the total number of animals using len()
Print the first and last animal using indexing
🔁 Part 3: For Loops & Ranges
✅ Q7. Print Numbers
Use range() and for loop to:

Print numbers from 1 to 10
Print even numbers from 2 to 20
Print multiples of 5 from 5 to 50
✅ Q8. Squares Table
Use a for loop to print square numbers from 1 to 10:

1 squared is 1  
2 squared is 4  
3 squared is 9  
...  
10 squared is 100  
🧠 Part 4: List Comprehension & Slicing
✅ Q9. Make a List of Cubes
Use list comprehension to generate cubes of numbers 1–5.
Print the list.
# Output:
[1, 8, 27, 64, 125]
✅ Q10. Top 3 Movies
Ask the user to enter 5 movie names using input().

Store them in a list.

Print:

The first 3 movies using slicing
The last 2 movies using slicing
✅ Q11. 🧑‍🏫 Top Students
Ask the user to enter names of 5 students using input() (one by one).

Store the names in a list.

Then:

Print a greeting for each student using a for loop.

Print only the top 3 students using slicing.

Copy the list using [:], then:

Add 2 new names to the copied list using .append()
Print both the original and the new list to show that the original is unchanged.
✅ Q12. ✈️ Travel Wishlist
Create a list of 5 places you want to visit.

Print the original list.

Print a temporarily sorted list using sorted().

Sort the list in reverse alphabetical order using .sort(reverse=True).

Use .reverse() twice:

First to flip and print the list
Then to flip it back and print again
🎯 Mini Challenge: Name Art Generator
Combine your understanding of input, lists, string slicing, for loops, and list length.

🧩 Task:
Ask the user to enter their name.

Convert the name to a list of characters.

Print each character on a new line using a for loop.

Then print:

The first 3 letters
The last 2 letters
The total number of letters using len()
🔍 Sample Output (for Jahanzaib)
J  
a  
h  
a  
n  
z  
a  
i  
b  

First 3 letters: ['J', 'a', 'h']  
Last 2 letters: ['i', 'b']  
Total letters: 9  
 
