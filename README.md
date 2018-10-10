# Create the below pattern using nested for loop in Python.
'''
*
* *
* * *
* * * *
* * * * *
* * * *
* * *
* *
*
'''

for i in range(1,5):
    for j in range(0,i):
        print("*", end='')
    print("\n")
    
for i in range(5,0,-1):
    for j in range(0,i):
        print("*", end='')
    print("\n")
