#include <stdio.h>
int main() {

    int a;
    printf("distance covered:");
    scanf("%d",&a);
    int x=a/5;
    
    if(a%5==0 ){
    printf ("steps required=%d\n",x);
    }else {
    printf ("steps required=%d\n",x+1);
    }
            
     return 0;
     
  }
