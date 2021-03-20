# Swapping of Two Number without 3rd Variable

```
#include<stdio.h>
int main(){
	int Number1 = 5; //2 bytes    
	int Number2 = 1; // 2 bytes   
	//int temp -> 2 bytes reduced by using 1, 2 and 3rd method
    
	printf("Value before swapping: Number1 = %d, Number2 = %d\n",Number1,Number2);
	
	// 1st method
	Number1 = Number1 + Number2; // 6
	Number2 = Number1 - Number2 ;// 5
	Number1 = Number1 - Number2; // 1
	
	// 2nd method
	Number1 = Number1 * Number2; // 5
	Number2 = Number1 / Number2; // 5
	Number1 = Number1 / Number2 ;// 1
	
	//3rd method 
	// XOR method : 1 1 -> 0      0 1 -> 1     1 0 -> 1   0 0 -> 0
	Number1 = Number1 ^ Number2; //  1 0 1 ^ 0 0 1 -> 1 0 0 -> 4
	Number2 = Number1 ^ Number2 ;//   1 0 0  ^ 0 0 1 -> 1 0 1 -> 5
	Number1 = Number1 ^ Number2; //   1 0 0 ^ 1 0 1 -> 0 0 1 -> 1
	
	printf("Value after swapping: Number1 = %d, Number2 = %d",Number1,Number2);
}
```

```
OUTPUT:
Value before swapping: Number1 = 5, Number2 = 1
Value after swapping: Number1 = 1, Number2 = 5
```
