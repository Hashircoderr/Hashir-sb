#reverse a string by using while loop in python
string=input("Enter a phrase: ")
i=0
m=1
A=str()
while i<len(string):
    A+=string[i-m]
    i+=1
    m+=2
print(A)
