#include<stdio.h>
int main()
{
  int n;
  scanf("%d",&n);
  int a[n];
  for(int i=0,fact=1;i<=n-1;i++)
  {
    fact=fact*a[i];
  }
  printf("\n");
  return 0;
}
