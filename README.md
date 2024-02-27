#include <stdio.h>
#include <stdlib.h>

int main()
{
    float a[5]={0.8,2.0,3.0,4.0,5.0};
    int b[5]={1,3,3,5,5};
    int m=0;
   for(int i=0;i<5;i++){
        printf("注射计量选择%.1f/%dml\n",a[i],b[m]);
        float q=a[i]/b[m];

   for(int j=10;j<=180;j+=10)
   {
       printf("注射次数%d次\n",j);
       float temp=q/j;
       printf("单次注射剂量为:%.2f/%d/%d=%.2fml\n",a[i],b[m],j,temp);

   }
    m++;
}
    return 0;
}
