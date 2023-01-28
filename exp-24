#include<stdio.h>
#include<conio.h>
int main()
{
    int decnum, rem, i=0;
    char hexnum[50];
    printf("Enter any decimal number: ");
    scanf("%d", &decnum);
    while(decnum!=0)
    {
        rem = decnum%16;
        if(rem<10)
            rem = rem+48;
        else
            rem = rem+55;
        hexnum[i] = rem;
        i++;
        decnum = decnum/16;
    }
    printf("\nEquivalent Value in Hexadecimal = ");
    for(i=i-1; i>=0; i--)
        printf("%c", hexnum[i]);
    getch();
    return 0;
}
