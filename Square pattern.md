# Square pattern

```
      1 2 3 4 5 
    1 * * * * *
    2 *       * 
    3 *       *
    4 * * * * *
```

```
#include<stdio.h>
int main(){
	
	for (int i=1;i<=4;i++){ // column
		for (int j=1;j<=5;j++){  // row
			if (j == 1 || j == 5 || i == 1 || i == 4){
				printf("* ");
			}
			else{
				printf("  ");
			}
		}
		printf("\n");
	}
	return 0;
}
```

```
OUTPUT:
* * * * *
*       *
*       *
* * * * *
```
