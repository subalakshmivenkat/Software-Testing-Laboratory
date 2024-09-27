# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:13-09-2024                                                                        
### REGISTER NUMBER : 212222040162

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
a)do-while:
```
def display(): 
    start=input("Enter a positive value for START: ") 
    end=input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric(): 
        while True: 
            start=int(start) 
            end=int(end) 
            print(start,end=' ') 
            if start<end: 
                start+=1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.")
display()
```
b) while..do
```
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric(): 
    start = int(start) 
    end = int(end) 
    while start < end: 
        print(start) 
        start += 1 
else: 
    print("Enter a valid positive number.")

```
c) if..else
```
def compare(): 
    a = input("Enter a value for A: ") 
    b = input("Enter a value for B: ") 
    try: 
        a = int(a) 
        b = int(b) 
        if a > b: 
            print("A is greater than B") 
        elif a < b: 
            print("B is greater than A") 
        else: 
            print("A is equal to B") 
    except ValueError: 
        print("Enter a valid number.")

compare()

```
d)switch
```
def switch(): 
    switcher = { 
        0: "even", 
        1: "odd" 
    } 
    n = input('Enter a value for N: ') 
    try: 
        n = int(n) 
        print(switcher[n % 2]) 
    except ValueError: 
        print("Enter a valid number.")

switch()

```
e) for
```
def iterate(): 
    string = input("Enter a string: ") 
    for i in string: 
        print(ord(i), end=" ") 

iterate()

```




### Output:
![Screenshot 2024-08-23 104445](https://github.com/user-attachments/assets/34a0fb5d-3bc7-4c09-bd63-e4b1867f019e)

![Screenshot 2024-08-23 103941](https://github.com/user-attachments/assets/fa3ce77d-c914-4ceb-9ef3-0a319e5568f9)

![Screenshot 2024-08-23 104742](https://github.com/user-attachments/assets/4a45534e-9ac0-485c-84a5-3f5c8135bc74)

![Screenshot 2024-08-23 105320](https://github.com/user-attachments/assets/6a494a2e-a1b1-40ae-910b-0cf00c8eab24)

![Screenshot 2024-08-23 110802](https://github.com/user-attachments/assets/be8658b9-070d-4b0b-8b4a-ea723106830b)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


