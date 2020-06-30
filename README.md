#include <stdio.h>


void main()
{
    int n,i ,s=0;
    float avg=0 ;
    printf("enter the range:\n");
    scanf("%d",&n);
    printf("enteries are:\n");
    for(i=1;i<=n;i++)
    {
        printf("%d\n",i);
    }
    for(i=1;i<=n;i++)
    {
        s+=i;
    }
    printf("sum=%d",s);
avg= (float)s/n;  //type casting
printf("\naverage=%f",avg);
  
}
