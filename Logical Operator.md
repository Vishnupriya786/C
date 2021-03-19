# Logical Operator

```
#include<stdio.h>
int main ()
{
	int Number1 = 3, Number2 = 4;
	int ResultForAnd = (Number1 != Number2) && (Number1 > Number2);
	int ResultForOr = (Number1 != Number2) || (Number1 > Number2);
	printf("%d\n",ResultForAnd);  
	printf("%d\n",ResultForOr);  
	// 0 ---> False, 1 ---> True 
}
```

```
OUTPUT:
0
1
```
