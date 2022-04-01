Задание 1
from math import sqrt

def distance (x1, y1, x2, y2):
    return sqrt((x1 - x2) ** 2 + (y1 -y2) ** 2)


x1 = float(input())
x2 = float(input())
y1 = float(input())
print(distance(x1, x2, y1, y2))

Задание 2
def min4(a, b, c, d):
    mas = [a, b, c, d]
    mas.sort()
    return mas[0]

print(min4(4, 5, 6, 7,))

Задание 3
def IsPointInSquare(x, y):
    if x ** 2 + y ** 2 <= 2 **(1/2) 
    -1 <= x +y <= 1
        return True

 x = float(input())
 y = float(input())
if IsPointInSquare(x, y):
    print("YES")
else:
    print("NO")       
    
    Задание 4
    def IsPointInSquare(x, y):
    return (abs(x) +abs(y)) <=1
 x, y = float(input()), float(input())
 if IsPointInSquare(x,y):
     print("YES")
else:
    print("NO")        
    
