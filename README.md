# Student--Grade-calculator
📌 Project: Student Grade Calculator , 
→Takes marks for 3 subjects
🔹 Calculates total and average 
🔹 Assigns grade using if-else conditions  🛠 Skills Used: ✔ Python basics ✔ Input &amp; Output ✔ Conditional statements  I’m practicing Python daily and sharing my learning journey.

#Python #BeginnerProject #LearningPython  #CodingJourney

#Student Grade Calculator,Each exam have 100 Marks
Maths=int(input("Enter the obtained Maths exam Marks:"))
Science=int(input("Enter the obtained Science exam Marks:"))
Social=int(input("Enter the obtained Social exam Marks:"))

Total=Maths+Science+Social
print(f"Total Marks:{Total}")

Average=Total//3
print(f"Average Marks:{Average}")

if Average>=90:
    print("Grade A allocated to Marks")
elif Average>=75:
    print("Grade B allocated to Marks")
elif Average>=50:
    print("Grade C allocated to Marks")
else:
     print("Fail.")
     
