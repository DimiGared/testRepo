import math
a = float(input('Enter a: '))
b = float(input('Enter b: '))
c = float(input('Enter c: '))
V =float(0)
S =float(0)
 
if a <= 0 or b <= 0 or c <= 0 or a + b <= c or a + c <= b or b + c <= a:
    print('Invalid triangle')
else:
   V = a * b * c;
  	printf("V  = %d\n", V);
  	S = 2*(a*c + b*c);
  	printf("S  = %d\n", S);
