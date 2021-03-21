# Pointers

```
Pointers used in C to make the code works efficient and faster in execution. 
it directly accesses the address of the variable.
```

```
#include<stdio.h>
int main(){
	int Number = 5;
	int *p;
	p = &Number;
	printf("The address of the variable 'Number' is %d and the value stored in that address is %d",p,*p);
}
```

```
OUTPUT:
The address of the variable 'Number' is 6487572 and the value stored in that address is 5
```
