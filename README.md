#include <stdio.h>

int main()
{
    int r;
    printf("Enter the value of Ram :");
    scanf("%d",&r);
    int s;
    printf("Enter the value of Shyam :");
    scanf("%d",&s);
    int a;
    printf("Enter the value of Ajay :");
    scanf("%d",&a);
    if(r>s && a>s){
        printf("Shyam is the youngest ");
    }
     if(s>r && a>r){
        printf("Ram is the youngest ");
    }
     if(r>a && s>a){
        printf("Ajay is the youngest ");
    }
    
    return 0;
}




