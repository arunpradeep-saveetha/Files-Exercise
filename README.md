## 1. Write a python program that writes “Hello world” into a file. EXAMPLE
```python
f=open("ex88.txt", 'w')
f.write("hello world")
f.close()
```
### OUTPUT SCREENSHOT
<img width="1481" alt="Screenshot 2024-11-26 at 11 29 31" src="https://github.com/user-attachments/assets/d6759886-b13a-436e-9d55-49ace30548ed">

## 2. Write a python program to create a text file “MyFile.txt” and ask the user to write separate 3 lines with three input statements from the user. EXAMPLE
```python
def program2():
  f=open("MyFile.txt", "w")
  linel=input("Enter the text:")
  line2=input("Enter the text:")
  line3=input("Enter the text:")
  new_line="\n"
  f.write(line1)
  f.write(new_line)
  f.write(line2)
  f.write(new_line)
  f.write(line3)
  f.write(new_line)
  f.close()
program2()
```
### OUTPUT SCREENSHOT

<img width="1481" alt="Screenshot 2024-11-26 at 11 36 04" src="https://github.com/user-attachments/assets/524d7cbc-372e-4e96-9a30-19f4a695e4f0">

## 3. Write a python program to find the total occurrences of a specific word from a text file.
```
cnt=0
word_search=input("Enter the words to search:")
with open("merge.txt","r")as f1:
for data in f1:
words=data.split()
for word in words:
if (word == word_search):
cnt+=1
print(word_search," found",cnt," times from the file")
program6()
```
## 4. Write a Python program to read first n lines of a file.

## 5. Write a Python program to know the cursor position and print the text according to below-given specification

  #### Print the initial position
  #### Move the cursor to 4th position
  #### Display next 5 characters
  #### Move the cursor to the next 10 characters
  #### Print the current cursor position
  #### Print next 10 characters from the current cursor position.

## 6. Write a Python program to append text to a file and display the text.
## 7. Write a python program that counts the number of tabs, spaces and newline characters in a file.
## 8. Write a python program to Replace all spaces from text with – (dash) in a text file.
## 9. Write a program to count a total number of lines and count the total number of lines starting with ‘A’, ‘B’, and ‘C’.
## 10. Write a python program that generates a Quiz and uses two files - Questions.txt and Answers.txt. The program opens Questions.txt and reads a question and displays the question with options on the screen. The program then opens the Answer.txt file and displays the correct answers.



