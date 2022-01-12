# findRemainder

#include <stdio.h> 
int main() {
    int T,A,B,remainder;
    scanf("%d",&T);
    while(T--)
    {
        scanf("%d " "%d\n",&A,&B);
        remainder = A % B;
        printf("%d\n",remainder);
    }
	return 0;
	}
