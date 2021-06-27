#include<stdio.h>
#include<string.h>
#include<stdlib.h>
void main()
{
char str[100];
int i=0;
printf("\n print individual characters of string in reverse order:");
printf("input the string:");
fgets(str,sizeof str,stdin);
l=strlen(str);
printf("the characters of the string in reverse are:");
for(str[l]='\0';l>=0;l--)
{
printf("%c",str[l]);
}
printf("\n");
}
