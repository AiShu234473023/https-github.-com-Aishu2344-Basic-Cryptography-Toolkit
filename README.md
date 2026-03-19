Introduction of Cryptigropy
1.What is cryptography?
Cryptography is the practice and study of techniques used to protect information by turning redable data Only people with the correct key or method can turn it back in to readable form.This help keep sensitive information safe from unauthorized people,such as hacker.
In the modern digital world ,miilon of people use password every day for emails,banking,social media,and apps.If password are stolen poorly,attackers can private account and cause big problems.
Main Focus of this project:Password Hashing and Salting.This project build as Basic cryptography tool a simple commond -line tool in python.
It demostrate the two very importent real-world cryptography techniques:
1.Salting:
- A"salt" is the random sring added to each password before hashing.
-This make sure that even i two users choose the same password(like ("password1234"),their stored hashes are completely different.
-Without salting,attackscan use pre-made table (raninbow table)
2.Password Hashhing
Hshing is one way process:it turns a password into a fixed-length string(hash)that can not be reversed back to the original password
-Example:"password123" become somthing like "5e3566574d0hjfshcsys4467gjkfdjd852"
Goal of the Project
The main goal is to create a working,education tool that shoe=ws how real system project password and generate secure random values.# https-github.-com-Aishu2344-Basic-Cryptography-Toolkit
