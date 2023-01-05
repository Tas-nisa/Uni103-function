# Uni103-function
There is all the code about function problems.

#include<stdio.h>
int is_even(int num){
  if(num%2==0)
    return 1;
  else
    return 0;
}
int main(){
  int num,result;
  printf("Enter any number to check if its even or odd number");
  scanf("%d",&num);
  result=is_even(num);
  if(result==1)
    printf("Its  even number");
  else
    printf("Its  odd number");
}
