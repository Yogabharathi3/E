# EX-05-5d-STRINGS
## AIM:
Write C program for the below pyramid string pattern.
Enter a string: PROGRAM
Enter number of rows: 5
P
R O
G R A
M P R O
G R A M P
R O G R A M
## ALGORITHM:
1. Input the number of rows for the pyramid (e.g., num_rows).
2. Initialize variables:i for the row count (starting from 1),j for the character count (starting from 1)
3. Start a loop for i from 1 to num_rows (for each row of the pyramid).
4. Calculate the midpoint position as midpoint = (2 * num_rows - 1) / 2.
5. End the program.
## PROGRAM:
```
#include<stdio.h>
int main()
{
  char str[20];
  int n,a=0;
  scanf("%[^\n]",str);
  scanf("%d",&n);
  for(int i=0;i<=n;i++)
{
    for(int j=0;j<=n-i;j++)
    {
    printf(" ");
    }

  for(int k=0;k<=i;k++)
  {
  printf("%2c",str[a++]);
  if(str[a]=='\0')
  a=0;
}
  printf("\n");
}
  return 0;
}
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/EX-05-5a-POINTERS/assets/118899387/619d747e-5e47-4304-a8d0-b40a8dc3f9a2)

## RESULT:
Thus the C program  has been executed successfully.
