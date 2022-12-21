# Testing1
//PRIME NUM
#include <stdio.h>
int n;
int prime(int n){
  int i,c=0;
  for (i=1;i<=n/2;i++){
       if (n%i==0)
          c++;      
  }
  if (c==1)
    printf("It is a Prime.");
  else
    printf("It is not a Prime.");
}
int main(){
    printf("Enter a number: ");
    scanf("%d",&n);
    prime(n);
}
