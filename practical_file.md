![](https://ce.gndec.ac.in/sites/default/files/logo.jpg)

*NAME -Hima gandhi*

*COLLEGE ROLL NO. -1921041*

*UNIERSITY ROLL NO.-1905339

#PROJECT pps#

_____________________________________________

```c

###1.TO FIND FIBONACCI SERIES

#include <stdio.h>

int main() {

int i, n, t1 = 0, t2 = 1, nextTerm;

printf("Enter the number of terms: ");

scanf("%d", &n);

printf("Fibonacci Series: ");

for (i = 1; i <= n; ++i) {

printf("%d, ", t1);

nextTerm = t1 + t2;

t1 = t2;

t2 = nextTerm;

}

return 0;

}

##OUTPUT-

Enter the number of terms:

9

Fibonacci Series: 0, 1, 1, 2, 3, 5, 8, 13, 21

```

```c

###2.TO FIND NUMBER IS EVEN OR ODD

#include<stdio.h>

int main()

{

int num;

printf("Enter any number:");

scanf("%d",&num);

if (num%2==0)

printf("Given number %d is Even \n",num);

else

printf("Given number %d is Odd \n",num);

return 0;

}

##OUTPUT-

Enter any number

5

Given number is odd

```

```c

###3.FACTORIAL OF A NUMBER USING RECURSION

#include<stdio.h>

long int multiplyNumbers(int n);

int main() {

int n;

printf("Enter a positive integer: ");

scanf("%d",&n);

printf("Factorial of %d = %ld", n, multiplyNumbers(n));

return 0;

}

long int multiplyNumbers(int n) {

if (n>=1)

return n*multiplyNumbers(n-1);

else

return 1;

}

##OUTPUT-

Enter a positive number

6

Factorial of 6=720

```

```c

### 4.TO CHECK WHETHER NUMBER IS POSITIVE OR NEGATIVE

#include<stdio.h>

int main()

{

int num;

printf("Enter any number: \n");

scanf("%d",&num);

if(num>0)

printf("%d is positive number \n",num );

else if(num<0)

printf("%d is negative number \n",num );

else

printf("You have entered value zero \n");

return 0;

}

##OUTPUT-

Enter any number

6

6 is positive number

```

```c

##5.TO FIND NUMBER IS PRIME OR NOT

#include<stdio.h>

int main()

{

int last;

printf("Enter number:");

scanf("%d",&last);

int prime,range=0;

for(int a=2;a<last;a++)

{

prime=0;

for(int i=2;i<last;i++)

{

if(last%i==0)

{

prime=prime+1;

printf("No\n");

break;

}

}

if(prime==0)

{

printf("Yes\n");

break;

}

break;

}

return 0;

}

##OUTPUT-

Enter number:

5

YES

```

```c

###6.TO FIND TABLE WITHIN THE RANGE

#include<stdio.h>

int main()

{

int n,i,range;

printf("Table of:");

scanf("%d",&n);

printf("Enter the range:");

scanf("%d",&range);

for(i=1;i<=range;++i)

{

printf("%d X %d = %d\n",n,i,n*i);

}

return 0;

}

##OUTPUT-

Table of:

2

Enter the range:

4

2 X 1 = 2

2 X 2 = 4

2 X 3 = 6

2 X 4 = 8

```

```c

###7.TO FIND TABLE

#include<stdio.h>

int main()

{

int i,j;

printf("Table of:");

scanf("%d\n",&j);

for(i=0;i<=10;i++)

printf("%d X %d = %d\n",j,i,j*i);

return 0;

}

##OUTPUT-

Table of:

3 x 0 = 0

3 X 1 = 3

3 X 2 = 6

3 X 3 = 9

3 X 4 = 12

3 X 5 = 15

3 X 6 = 18

3 X 7 = 21

3 X 8 = 24

3 X 9 = 27

3 X 10 = 30

```

```c

###8. TO DISPLAY THE TABLE OF EVEN NUMBER

#include<stdio.h>

int main()

{

int i,j;

printf("Table of:");

scanf("%d\n",&j);

if(j%2==0)

{

for(i=0;i<=10;i++)

printf("%d X %d = %d\n",j,i,j*i);

}

else

{

printf("Number is not even\n");

}

return 0;

}

##OUTPUT-

Table of:

3

Number is not even

```

```c

###9.TO CONVERT TEMPERATURE FROM FAHRENHEIT TO CENTIGRADE

#include<stdio.h>

int main()

{

float celcius,fehrenheit;

printf("Please enter the temperature in fehrenheit: \n");

scanf("%f",&fehrenheit);

celcius=(fehrenheit-32)*5/9;

printf("\n %.2f fehrenheit= %.2f celcius \n", fehrenheit,celcius);

return 0;

}

##OUTPUT-

Please enter the temperature in fehrenheit:

212

212 fahrenheit=100 celcius

```

```c

###10.TO MULTIPLY TWO NUMBERS

#include<stdio.h>

float multi(float a,float b);

int main()

{

float m,n;

printf("\n Please enter a number : \n");

scanf("%f",&m);

printf("\n Please add another number\n");

scanf("%f",&n);

float result=multi(m,n);

printf("result is %.5f\n",result);

}

float multi(float a,float b)

{

float multiple=a*b;

return(multiple);

}

##OUTPUT-

Please enter a number:

3

Please enter another number:

4

result is 12

```

```c

##11.TRIANGULAR PYRAMID

#include<stdio.h>

int main()

{

int n,i,j;

printf("Enter number of rows you want to print for pyramid:\n");

scanf("%d",&n);

for(i=1;i<=n;i++)

{

for(j=1;j<=2*n-1;j++)

{

if(j>=n-(i-1) && j<=n+(i-1))

printf("*");

else

printf(" ");

}

printf("\n");

}

return 0;

}

##OUTPUT-

Enter number of rows you want for pyramid:

4

*

* *

* * *

* * * *

```

```c

###12.TO FIND HCF OF 2 NUMBERS:

#include<stdio.h>

int main(){

int a,b,i,hcf;

printf("Enter 1st integer:\n");

scanf("%d",&a);

printf("enter 2nd intger:\n");

scanf("%d",&b);

for(int i=1;i<=a||i<=b;i++)

{

if(a%i==0 && b%i==0)

hcf=i;

}

printf("hcf=%d",hcf);

return 0;

}

##OUTPUT-

Enter 1st integer

4

Enter 2nd interger

6

hcf=2

```

```c

###13.TO FIND LCM OF 2 NUMBERS

#include<stdio.h>

int main(){

int a,b,i,lcm,gcd;

printf("Enter 1st integer:\n");

scanf("%d",&a);

printf("enter 2nd intger:\n");

scanf("%d",&b);

printf("\n");

for(int i=1;i<=a&&i<=b;i++)

{

if(a%i==0 && b%i==0)

gcd=i;

}

lcm=(a*b)/gcd;

printf("lcm=%d",lcm);

return 0;

}

##OUTPUT-

Enter 1st integer

5

Enter 2nd integer

7

lcm=1

```

```c

###14.TO CHECK NUMBER IN ARRAY

#include<stdio.h>

int main()

{

int arra[5]={1,5,8,2,7};

int c;

printf("Enter the number you want to check");

scanf("%d",&c);

for(int i=0;i<5;i++)

{

if(c==arra[i])

{printf("yes");}

else

printf("no");

}

return 0;

}

##OUTPUT-

Enter the number you want to check

9

no

```

```c

###15.TO FIND NUMBER IS ARMSTRONG

#include<stdio.h>

int main(){

int no,n,r,c,sum=0;

printf("Enter a number:\n");

scanf("%d",&n);

no=n;

while(n>0)

{

r=n%10;

c=r*r*r;

sum=sum+c;

n=n/10;

}

if(no==sum)

printf("The given number %d is an armstrong number\n",no);

if(no!=sum)

printf("The given number %d is not an armstrong number\n",no);

return 0;

}

##OUTPUT-

Enter a number

9

The given number 9 is an armstrong number

```

```c

###16.TO CALCULATE SUM OF DIGITS

#include<stdio.h>

int sum(int c);

int main()

{

int a,b;

printf("Please enter a number to calculate the sum of digits:\n");

scanf("%d",&a);

b=sum(a);

printf("Sum is%d\n",b);

}

int sum(int c)

{

int sum1=0,n;

while(c!=0)

{

sum1=sum1+c%10;

c=c/10;

}

return sum1;

}

##OUTPUT-

Please enter a number to calculate the sum of digits:

23

Sum is5

```

```c

###17.TO CALCULATE AVERAGE OF 5 NUMBERS

#include<stdio.h>

int avg(int a,int b,int c,int d,int e);

int main()

{

int a,b,c,d,e,f;

printf("Enter 5 numbers:\n");

scanf("%d %d %d %d %d",&a,&b,&c,&d,&e);

f=avg(a,b,c,d,e);

printf("avg is %d",f);

}

int avg(int a,int b,int c,int d,int e)

{

int ans;

ans=(a+b+c+d+e)/5;

//printf("The average of entered 5 numbers %3.f %3.f %3.f %3.f %3.f is %3.f",a,b,c,d,e,ans);

return ans;

}

##OUTPUT-

Enter 5 numbers

3,5,7,5,8

The average of entered 5 numbers is3,5,7,5,8 is 27

```

```c

###18.TO FIND LEAP YEAR

#include <stdio.h>

int main()

{

int year;

printf("Enter a year: ");

scanf("%d", &year);

if (year % 4 == 0)

{

if (year % 100 == 0)

{

if (year % 400 == 0)

printf("%d is a leap year.", year);

else

printf("%d is not a leap year.", year);

}

else

printf("%d is a leap year.", year);

}

else

printf("%d is not a leap year.", year);

return 0;

}

##OUTPUT-

Enter a year:

2019

2019 is not a leap year

```

```c

19.FIND LARGEST AMONG THE THEREE NUMBERS

#include <stdio.h>

int main() {

double n1, n2, n3;

printf("Enter three different numbers: ");

scanf("%lf %lf %lf", &n1, &n2, &n3);

if (n1 >= n2 && n1 >= n3)

printf("%.2f is the largest number.", n1);

if (n2 >= n1 && n2 >= n3)

printf("%.2f is the largest number.", n2);

if (n3 >= n1 && n3 >= n2)

printf("%.2f is the largest number.", n3);

return 0;

}

##OUTPUT-

Enter three different numbers:

4,5,8

8 is the largest number.

```

```c

###20.PROGRAM TO CHECK ALPHABET

#include <stdio.h>

int main() {

char c;

printf("Enter a character: ");

scanf("%c", &c);

if ((c >= 'a' && c <= 'z') || (c >= 'A' && c <= 'Z'))

printf("%c is an alphabet.", c);

else

printf("%c is not an alphabet.", c);

return 0;

}

##OUTPUT-

Enter a character:

z

z is an albhabet

```c
