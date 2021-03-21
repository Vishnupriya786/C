# Recursion

```
#include<stdio.h>
int factorial(int);
int main(){
	int result = factorial(4);
	printf("%d",result);
}

int factorial(int Number){
	if (Number!=1){
		return Number * factorial(Number-1);
	}
}
```

```
OUTPUT:
24
```
