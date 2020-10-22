print("დავალება---1")
def avg(num1,num2):
    print("საშუალო: ",end="")
    return (num1+num2)/2
print(avg(5, 6))
print(avg(7, 9))
print(avg(5, 2))
print("დავალება---2")
def avg(num1,num2):
    s = (num1+num2)/2
    print("საშუალო: ",s) 
avg(5, 6)
avg(7, 9)
avg(5, 2)
print("დავალება---3")
def cube(num):
    print("რიცხვის კუბი: ",end="")
    return num**3
print(cube(5))
print(cube(7))
print(cube(9))
print("დავალება---4")
def m(num1,num2):
    if num1>num2:
        print("მინიმალური რიცხვი: ",end="")
        return num1
    elif num2>num1:
        print("მინიმალური რიცხვი: ",end="")
        return num2
    else:
        print("რიცხვები ტოლია")
print(m(5, 6))
print(m(7, 9))
print(m(5, 2))
print("დავალება---5")
def odd(num):
    if num%2==0:
        return False
    else:
        return True
print(odd(5))
print(odd(7))
print(odd(2))
print("დავალება---6")
def factorial_count(n):
    factorial = 1
    if n==0:
        print("ფაქტორიალი: ",1)
    else:
        for i in range(1,n+1):
            factorial = factorial*i
        return factorial
number = int(input("შეიყვანეთ მთელი რიცხვი: "))
print("ფაქტორიალი: ",factorial_count(number))
print("დავალება---7")
def factorial_recursive(n):
    if n == 1:
        return 1

    # Recursive case: n! = n * (n-1)!
    else:
        return n * factorial_recursive(n-1)
number = int(input("შეიყვანეთ მთელი რიცხვი: "))
print("ფაქტორიალი: ",factorial_recursive(number))
print("დავალება---8")
numbers = [5,12,52,4,9]
sum = 0
for i in numbers:
    sum+=i
print("რიცხვების ჯამი: ",sum)
maximum = max(numbers)
minimum = min(numbers)
avg = sum/len(numbers)
print("მაქსიმალური მნიშვნელობა: ",maximum)
print("მინიმალური მნიშვნელობა: ",minimum)
print("საშუალო არითმეტიკული: ",avg)
numbers.append(102)
print("102 დამატებული ბოლოში: ",numbers)
numbers.insert(2,205)
print("205 მესამე პოზიციაზე: ",numbers)
numbers.pop(3)
print("ამოვშალოთ მე-4 ელემენტი: ",numbers)
numbers.sort()
print("დალაგება ზრდადობით: ",numbers)
print("დავალება---9")
def com(l1,l2):
    l = list(set(l1).intersection(l2))
    if l:
        return True
    else:
        return False
list1 = [1,2,3,4,5,6]
list2 = [3, 5, 7, 9]
print(com(list1,list2))
print("დავალება---11")
import numpy as n
first = n.array([1, 2, 3, 4])
second = n.array([2, 3, 4, 5])
third = n.add(first,second)
print(third)
import numpy as np
randnums1= np.random.randint(1,101,5)
randnums2= np.random.randint(1,101,5)
result=[]
for i in range(0,5):
  result.append(randnums1[i]+randnums2[i])
print(randnums1)
print(randnums2)
print("sum: ",result)
print("დავალება---13")
import numpy as n
first = n.array([1, 2, 3, 4])
second = n.array([2, 3, 4, 5])
  
print ("1st Input  number : ", first) 
print ("2nd Input  number : ", second) 
    
multi = n.multiply(first, second)  
print ("output number : ", multi)  
import numpy as np
randnums1= np.random.randint(1,101,5)
randnums2= np.random.randint(1,101,5)
multi = np.multiply(randnums1, randnums2) 
print(randnums1)
print(randnums2)
print("multiply: ",multi)


























