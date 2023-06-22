//In an array (sum of odd places) and (sum of even places) 
#include<stdio.h>
int main()
{
    int n,i,j=0,k=1,evensum,oddsum;
    scanf("%d",&n);
    int a[n];
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    evensum=0;
    for(j;j<n;j=j+2)
    {
     evensum=evensum+a[j];   
    }
    printf("%d",evensum);
    printf("\n");
    oddsum=0;
    for(k;k<n;k=k+2)
    {
        oddsum=oddsum+a[k];
    }
    printf("%d",oddsum);
    return 0;

}
