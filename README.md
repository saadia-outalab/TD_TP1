# TD_TP1
langage c
#include <stdio.h>
#include <math.h>
main()
//declaration de variable
int n,s,p,i;
//initialisation
s=0;
p=1;
i=2;
while(i<=n)
{
s+=i;
p*=i;
i+=2;
}
printf("s=%d,p=%d",s,p);
