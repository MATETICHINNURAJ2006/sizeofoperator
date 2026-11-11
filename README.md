#include <stdio.h>
int main() 
{
    char a='g';;;
    int b=10;
    float c=6.88;
    double d=66665554;
    printf("Size of char is:%zu\n",sizeof(a)); 
    printf("Size of integer is:%zu\n",sizeof(b));
    printf("Size of float is:%zu\n",sizeof(c));
    printf("Size of double is:%zu\n",sizeof(d));
    return 0;
}                                                                      
