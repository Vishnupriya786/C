# User defined Function return

```
#include<stdio.h>
int sum(int, int);  // declaration
int main(){
    int Result = sum(5,4);   // calling function
    printf("%d",Result);
	return 0;
}

int sum(int Number1, int Number2){  // definition
	return Number1 + Number2;
}
```

```
OUTPUT:
9
```
