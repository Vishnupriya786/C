# Structure

```
Structure in C is used to store data.
```

```
#include<stdio.h>
struct login{
	char Name[20];
    int Quantity;
};
int main(){
	struct login n, q;
	
	printf("Enter Name: ");
	scanf("%s",n.Name);
	printf("enter Quantity: ");
	scanf("%d",&q.Quantity);
	
	printf("Welcome %s! you booked %d tickets successfully",n.Name,q.Quantity);
}
```

```
OUTPUT:
Enter Name: vishnupriya
enter Quantity: 2
Welcome vishnupriya! you booked 2 tickets successfully
```
