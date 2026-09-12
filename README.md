print("--------STUDENT RESULT MANAGEMENT SYSTEM--------")
name = input("Student name:")
roll_no =int(input("Enter Roll Number:"))
department = input("Enter Department:")
python = int(input("Enter Python Mark:"))
english = int(input("Enter English Mark:"))
maths = int(input("Enter Maths Mark:"))
# calculate total and average
total = python + english + maths
average = total/3
#calculate grade
if average >=90:
    grade = "A+"
elif average >=80:
    grade = "A"
elif average >=70:
    grade = "B"
elif average >=60:
    grade = "C"
elif average >=50:
    grade = "D"    
else:
    grade = "E"
#PASS OR FAIL
if (python >=35 and english >=35 and maths >=35):
   result= "PASS" 
else:
    result= "FAIL"
print("--------------------------")
print("------STUDENT MARK SHEET-------")
print("--------------------------")
print("Name:",name)
print("Roll No:",roll_no)
print("Department:",department)
print("Python:",python)
print("English:",english)
print("Maths:",maths)
print("Total:",total)
print("Average:",average)
print("Grade:",grade)
print("Result:",result)
print("--------------------------")
