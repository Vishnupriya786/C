# Swapping of Two Number

```
#include<stdio.h>
int main(){
	int Number1 = 48;
	int Number2 = 50;
	int temp;
	printf("Value before swapping: Number1 = %d, Number2 = %d\n",Number1,Number2);
	temp = Number1;  //temp = 48
	Number1 = Number2; // Number1 = 50
	Number2 = temp; // Number2 = 48
	printf("Value after swapping: Number1 = %d, Number2 = %d",Number1,Number2);
}
```

```
OUTPUT:
Value before swapping: Number1 = 48, Number2 = 50
Value after swapping: Number1 = 50, Number2 = 48
```
