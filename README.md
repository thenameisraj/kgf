#include<iostream.h>
#include<conio.h>
#include<math.h>
class funoverload
{
public:
double area(double side)
{
return (side*side);
}
double area(double l,double b)
{
return (l*b);
}
double area(double a,double b,double c)
{
double S;
S=(a+b+c)/3;
return(sqrt((s-a)*(s-b)*(s-c)));
}
};
void main()
{
funoverload f;
cout<<"\n area of square="<<f.area(5.00);
cout<<"\n area of rectanlge="<<f.area(5.0,7.75);
cout<<"\n area of triangle="<<f.area(2.0,7.0,9.0);
getch();
}
