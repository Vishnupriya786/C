# Swapping of Two number easy way

```
#include<stdio.h>
int main(){
	int Number1 = 5; //2 bytes    
	int Number2 = 1; // 2 bytes   
	printf("Value before swapping: Number1 = %d, Number2 = %d\n",Number1,Number2);
	
	Number2 = Number1 + Number2 - (Number1 = Number2);
	
	printf("Value after swapping: Number1 = %d, Number2 = %d",Number1,Number2);
}
```

```
OUTPUT:
Value before swapping: Number1 = 5, Number2 = 1
Value after swapping: Number1 = 1, Number2 = 5
```
