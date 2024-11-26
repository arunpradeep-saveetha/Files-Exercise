##1. Write a python program that writes “Hello world” into a file.
```
f=open("ex88.txt", 'w')
f.write("hello world")
f.close()
```
##2. Write a python program to create a text file “MyFile.txt” and ask the user to write separate 3 lines with three input statements from the user.
```
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
##3. Write a python program to find the total occurrences of a specific word from a text file.
##4. Write a Python program to read first n lines of a file.
##5. Write a Python program to know the cursor position and print the text according to below-given specifications:
    #Print the initial position
    #Move the cursor to 4th position
    #Display next 5 characters
    #Move the cursor to the next 10 characters
    #Print the current cursor position
    #Print next 10 characters from the current cursor position.

