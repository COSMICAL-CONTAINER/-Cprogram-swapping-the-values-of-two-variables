# -Cprogram-swapping-the-values-of-two-variables
swapping the values of two variables without a third variable

Here are two ways you can try  

way1:

#include <stdio.h>
int main()
{
    int a = 3, b = 4;
    printf("before:a=%d,b=%d\n",a,b);
    a = a + b;
    b = a - b;
    a = a - b;
    printf("after:a=%d,b=%d\n",a,b);
    return 0;
}


way2:

#include <stdio.h>
int main()
{
    int a = 3, b = 4;
    printf("before:a=%d,b=%d\n",a,b);
    a = a^b;
    b = a^b;
    a = a^b;
    printf("after:a=%d,b=%d\n",a,b);
    return 0;
}
