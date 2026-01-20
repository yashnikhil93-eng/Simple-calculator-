# Simple-calculator-

name = input("Enter student name: ")

marks = []
subjects = ["Math", "Science", "English", "Computer", "Social"]

for subject in subjects:
    score = float(input(f"Enter marks for {subject}: "))
    marks.append(score)

total = sum(marks)
average = total / len(marks)

if average >= 90:
    grade = "A+"
elif average >= 80:
    grade = "A"
elif average >= 70:
    grade = "B"
elif average >= 60:
    grade = "C"
else:
    grade = "Fail"

print("\n----- Result -----")
print("Name:", name)
print("Total Marks:", total)
print("Average:", average)
print("Grade:", grade)



