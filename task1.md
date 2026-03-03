# task.md
student_marks = {"sumit":95,
                 "aman":90,
                 "alice":85,
                 "pardeep":80
                 }
name = input("enter the student's name: ").strip()
if name in student_marks:
    print(f"{name}'s marks: {student_marks}")
else:
    print(f"student not found ")

