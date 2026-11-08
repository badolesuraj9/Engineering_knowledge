# STUDENT RESULT MANAGEMENT SYSTEM

print("========================================")
print("      STUDENT RESULT MANAGEMENT SYSTEM")
print("========================================")


# FUNCTION 1: Calculate Grade

def calculate_grade(percentage):

    if percentage >= 90:
        return "A+"

    elif percentage >= 80:
        return "A"

    elif percentage >= 70:
        return "B"

    elif percentage >= 60:
        return "C"

    elif percentage >= 35:
        return "D"

    else:
        return "F"


# FUNCTION 2: Main Program

def student_result():

    # Step 1: Accept Student Details

    name = input("\nEnter Student Name: ")

    roll_no = input("Enter Roll Number: ")


    # Step 2: Create Subject List

    subjects = [
        "English",
        "Mathematics",
        "Science",
        "Computer",
        "Physics"
    ]

    marks = []

    print("\nEnter Marks (0-100):")


    # Step 3: Accept Subject Marks

    for subject in subjects:

        mark = int(input("Enter " + subject + " Marks: "))

        marks.append(mark)


    # Step 4: Calculate Total Marks

    total = sum(marks)

    maximum_marks = 500


    # Step 5: Calculate Percentage

    percentage = (total / maximum_marks) * 100


    # Step 6: Check Pass or Fail

    if all(mark >= 35 for mark in marks):

        result = "PASS"

        grade = calculate_grade(percentage)

    else:

        result = "FAIL"

        grade = "F"


    # Step 7: Display Final Result

    print("\n========================================")

    print("             STUDENT RESULT")

    print("========================================")

    print("Student Name:", name)

    print("Roll Number:", roll_no)

    print("----------------------------------------")

    for i in range(len(subjects)):

        print(subjects[i], ":", marks[i])

    print("----------------------------------------")

    print("Total Marks:", total, "/", maximum_marks)

    print("Percentage:", round(percentage, 2), "%")

    print("Grade:", grade)

    print("Final Result:", result)

    print("========================================")


# CALL THE FUNCTION

student_result()
