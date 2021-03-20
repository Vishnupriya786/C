# 2D Array

```
          0  1  2
          --------
     0->  1  2  3 
     1->  4  5  6 
     2->  7  8  9
     3->  10 11 12
```

```
#include<stdio.h>
int main(){
	int Twodarray[5][8] = {{1,2,3},{4,5,6},{7,8,9},{10,11,12}};
	for (int i = 0;i<4;i++){
		for (int j=0;j<3;j++){
			printf("%d ",Twodarray[i][j]);
		}
		printf("\n");
	}
	
	return 0;
}
```

```
OUTPUT:
1 2 3
4 5 6
7 8 9
10 11 12
```
