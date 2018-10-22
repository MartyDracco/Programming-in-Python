# Programming-in-Python
Some basic code files made in PyCharm that include few functions, some of them use libraries. 

strana=float(input("Define side of a square"))

number_is_correct = side>0

if number_is_correct:
    print"Square perimeter with side a", side, "is", 4 * side, "cm"
    print"Square area with side a", strana, "is", side * side, "cm2"
else:
    print"The side must have value higher than 0"

number = int(input("Define integer, I'll add 3 to it"))
if number == 0:
    print("Yay, that's easy")
print number, "+ 3 =", number+3

age = int(input("How old are you?"))
if age >= 150:
    print"What planet are you from?"
elif age >= 18:
    print"Can we offer wine or beer or other alcoholic drink?"
elif age >= 1:
    print"May I offer you milk, tea or hot chocolate?"
elif age >= 0:
    print"Unfortunately, baby food is out of stock"
else:
    print"Visitors from the past, please return to Tardis! We dont want to create any time travel paradoxes here."
