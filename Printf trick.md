# Printf trick

```
#include<stdio.h>
int main(){
	#define Name printf("Vishnupriya") // printf statement not requires ";" when used with preprocessor
	Name;
	return 0;
}
```

```
OUTPUT:
Vishnupriya
```
