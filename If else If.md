# If else If

```
#include<stdio.h>
int main()
{
	int Number1 = 6, Number2 = 18, Number3 = 9;
	if ((Number1 > Number2) && (Number1 > Number3)){
		printf("%d is greater",Number1);
	}
	else if(Number2 > Number3){
		printf("%d is greater",Number2);
	}
	else{
		printf("%d is greater",Number3);
	}
	
}
```

```
OUTPUT:
18 is greater
```
