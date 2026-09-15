#include <stdio.h>

int main()
{
    int marks;
    float income;

    printf("Enter marks: ");
    scanf("%d", &marks);

    printf("Enter family income: ");
    scanf("%f", &income);

    if (marks >= 80 || income < 50000)
        printf("Eligible for Scholarship");
    else
        printf("Not Eligible for Scholarship");

    return 0;
}
