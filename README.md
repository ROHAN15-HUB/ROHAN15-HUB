
// program for checking element is present or not by Rohan #include<stdio.h>
void main ()
{
int a[10],i,check;
printf("enter the array\n");
for(i=0;i<10;i++)
{
scanf("%d",&a[i]);
}
printf("enter the element u want to check\n");
scanf("%d",&check);
for(i=0;i<10;i++)
{
if(check==a[i])
{
printf("present");
}
else
{
printf("not present");
break;
}
}
}
