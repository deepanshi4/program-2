# program-2
 a Python program to accept a filename from the user and print the extension of that.
filename=input("write the filename")
file_extns=filename.split(".")
print("the extension is"+repr(file_extns[1]))
