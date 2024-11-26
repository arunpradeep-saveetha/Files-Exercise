## Write a python program that writes “Hello world” into a file.
```
f=open("ex88.txt", 'w')
f.write("hello world")
f.close()
```
## Write a python program to create a text file “MyFile.txt” and ask the user to write separate 3 lines with three input statements from the user.
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
