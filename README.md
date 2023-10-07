# cucumber-s
import math
t = -20
k = 10
#y = 5
def сдвиг_массива(arr, k):
    for _ in range(k):
        for i in range(len(arr)):
            arr[i] = arr[i] + 2
    return arr

mass = list(range(1,100))
shift = k
res = сдвиг_массива(mass, shift)
print(mass)
for i in range(shift):
    z = sum(res)
    x1 = mass[1] + mass[2]
    x2 = (z + x1 + t)**2

print('x2=', x2)
x3 = (math.sqrt(x2)) - z - x1
#x4 = x2 - z - x1 - t
print('x3=', x3)
#print(x4)

