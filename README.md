#include <stdio.h>
int main(){
      printf(“25331A05D6\n”);
    int arr[5]={10,20,30,40,50};
    int *p=arr;
    printf("%d\n",*p);
    printf("%d\n",*(p+1));
    printf("%d\n",*(p+2));
    p++;
    printf("%d\n",*p);
    return 0;
}
