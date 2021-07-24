#include <stdio.h>
void main()
{
    int i,a[100],n,m=1;
    printf("Enter the size of array ");
    scanf("%d",&n);
    printf("Enter the array elements ");
    for(i=0;i<n-1;i++){
        scanf("%d",&a[i]);
    }
    i=0;
    while(a[i]==m){
        m++,i++;
    }
    printf("Missing Value %d",m++);
}