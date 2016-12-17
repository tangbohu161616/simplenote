#include<stdio.h>
int main()
{
  int a=1;
  for(;a<33;a++)
  {
    if(a%3==0)
      printf("%d do the first question\n",&a);
    else if(a%3==1)
      printf("%d do the second question\n",&a);
    else if(a%3==2)
      printf("%d do the third question\n",&a);
    else
      printf("%d do the four question\n",&a);
  }
  return 0;
}
