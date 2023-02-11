# EVEN-OR-ODD.C
CHECKING EVEN OR ODD NUMBER WITH C PROGRAMMING.
#include<stdio.h>
int main(){
    int a;
    printf("ENTER THE NUMBER: ");
    scanf("%d",&a);
    //enter the number of any choose
    if (a%2==0){
        printf("NUMBER IS EVEN");
      
    }
    //entered number is even
    else if(a==0){
        printf("NUMBER IS ZERO");
        
    }
    //entered number is zero
    else{
        printf("NUMBER IS ODD");
        
    }
    //entered number is odd
    return 0;
}
