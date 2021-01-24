# ML100Days
# HW-D02
import numpy as np

array1 = np.array(range(30))

q1 = array1.ravel(order='F').reshape(5, 6)
print(q1)

array2 = array1[array1%6 == 1]
for i in array2:
    print(i)

