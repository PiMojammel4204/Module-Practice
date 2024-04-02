# Module-Practice
#include <stdio.h>
int main()
{
    printf("“Recently I heard that you’ve achieved 95%% marks in your exam. \n");
    printf("This is brilliant! \n");
    printf("I wish you’ll shine in your life!    Good luck with all the barriers(/\\) in your life.\n");
    
    return 0;
}

#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d %d",&a,&b);

    printf("%d + %d = %d\n",a,b,a+b);
    printf("%d - %d = %d\n",a,b,a-b);
    printf("%d * %d = %d\n",a,b,a*b);
    printf("%d / %d = %.2f\n", a, b, (float)a / b);5

    return 0;
} 

#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if(a%2==0)
        printf("even");
    else
        printf("odd");
    return 0;
}

prblm 4

#include <stdio.h>

int main() {
    int num;

    scanf("%d", &num);

    if (num > 0)
        printf("positive\n");
    else if (num < 0)
        printf("negative\n");
    else
        printf("zero\n");

    return 0;
}
