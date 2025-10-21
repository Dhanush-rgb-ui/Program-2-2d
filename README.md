# Module-2 Day-4 SEB
## AIM:
To write a C program for the following pattern:

<img width="467" height="298" alt="image" src="https://github.com/user-attachments/assets/abb0c39d-9f13-4dae-9761-db4c04ff23a6" />

## Program:
```c
#include<stdio.h>
 
int main()
{
  int i,j;
  for(i=0;i<=12;i++){
      //numbers
      for(j=12-i+1;j<=12;j++){
          printf("%d ",j);
      }
      //zeros
      int brek=i;
      if(i==brek){
          printf("0 ");
      }
      //numbers
      for(j=12;j>12-i;j--){
          printf("%d ",j);
      }
      printf("\n");
  }
 return 0;
}

```
## Result:
<img width="1000" height="342" alt="image" src="https://github.com/user-attachments/assets/015c36d4-33ec-4de5-9267-3e3585ebec75" />
