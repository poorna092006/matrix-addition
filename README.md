#include <stdio.h>

int main() {
   int A[2][2]={ {10,20}, {30,40} };
   int B[2][2]={ {50,60}, {70,80} };
   int C[2][2];
   int i,j;
   
   printf("Matrix A\n");
   for(i=0;i<2;i++)
   {
       for(j=0;j<2;j++)
   {
       printf("%d ",A[i][j]);
   }
       printf("\n");
   }
   printf("Matrix B\n");
   for(i=0;i<2;i++)
   {
       for(j=0;j<2;j++)
   {
     printf("%d ",B[i][j]);
   }
      printf("\n");
   }
   printf("Addition is\n");
   for(i=0;i<2;i++)
   {
       for(j=0;j<2;j++)
   {
     C[i][j]=A[i][j]+B[i][j];     
     printf("%d ",C[i][j]);

   }
      printf("\n");
   }
        
   
   
   return 0;
}
