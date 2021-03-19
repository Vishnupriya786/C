# Left Right Shift Operator

```
#include<stdio.h>
int main ()
{
	int LeftShift = 8 << 2;  // 1 0 0 0 0 0 . -> 32
	int RightShift = 8 >> 2 ; // 1 0 0 0 -> 1 0 -> 2
	printf("%d\n", LeftShift);
	printf("%d\n", RightShift);
}
```

```
OUTPUT:
32
2
``` 
