# File Handling Mini Project  
#Write & Read Student Data (Python Project)


#Python Code

python
#File: write_read_student.py

#Writing Student Data to a File
students = [
    "101, Riya, 89",
    "102, Arjun, 76",
    "103, Meera, 92"
]

with open("students.txt", "w") as f:
    for s in students:
        f.write(s + "\n")

print("Student data written successfully!")

#Reading Student Data from the File 
with open("students.txt", "r") as f:
    data = f.read()

print("\nReading Data from File:")
print(data)




Output


Student data written successfully!

Reading Data from File:
101, Riya, 89
102, Arjun, 76
103, Meera, 92





