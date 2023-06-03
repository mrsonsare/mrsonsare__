#include <stdio.h>

int main()
{
 int x;
 int y;
 printf("Enter Cost price :");
 scanf("%d",&x);
 printf("Enter Selling price :");
 scanf("%d",&y);
 int z;
 z= y-x;

 if(z>x){
     printf("Profit:%d",z);
 }
else{
    printf("Loss:%d",z);
}
if(z<0){
    z = z *(-1);
}
    return 0;
}
