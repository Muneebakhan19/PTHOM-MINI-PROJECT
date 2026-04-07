age=int(input("Enter age: "))
if age>=18:
    print("you are eligible to vote")
else:
    print("you re not eligible to vote")
​
Enter age: 112
you are eligible to vote






n=int(input("ENTER A NUMBER: "))
for i in range (1,11,1):
    print(n*i)
​
​
ENTER A NUMBER: 12
12
24
36
48
60
72
84
96
108
120






numbers=[12,100,47,56,78,52,59,90]
greatest=numbers[0]
for num in numbers:
    if num>greatest:
        greatest=num
        print("Greatest number:",greatest)


​
​
Greatest number: 100
