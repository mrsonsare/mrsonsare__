
#include <stdio.h>

int main()
{
    int n;
    printf("Enter the value :");
    scanf("%d",&n);
    
for(int i=n;i<=n*10;i=i+n){
    printf("%d",i);
    printf("\n");
}

    return 0;
}


