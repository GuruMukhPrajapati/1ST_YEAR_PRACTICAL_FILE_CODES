## Authors

- [@GuruMukhPrajapati](https://github.com/GuruMukhPrajapati)



## ALL OUTPUTS RUNNING WELL I ADD VALUE ON MY SIDE YOUR VALUE WILL BE ACCOUDING TO YOU 

 ## 1. SWAPPING TWO NUMBERS [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/add_of_given_serias.c)

 
![Screenshot (51)](https://user-images.githubusercontent.com/117162170/218599348-ff661941-5b08-459f-ab63-43f0faab8611.png)
## DIRECT CODE 

swapping numbers

```bash
  #include <stdio.h>
#include<conio.h>
void main(){
int a,b,c;
clrscr();
printf("the value of a and b  : ");
scanf("%d%d",&a&b);
printf("\n befor swapping a=%d,\t b=%d"a,b);
c=a;
a=b;
b=c;
printf("\n\nafter swaping a=%d,\t b=%d"a,b);
getch();
}
```

## 2.SIMPLE INTERST [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/simple_interst.c)
![Screenshot (52)](https://user-images.githubusercontent.com/117162170/218599390-b5237cc0-9443-425d-a15b-3935de601220.png)
## DIRECT CODE 

simple interst

```bash
  #include <stdio.h>
#include <conio.h>
void main()
{
    float principal, rate, time, interest;
    clrscr();
    printf("Enter the principal amount: ");
    scanf("%f", &principal);
    printf("Enter the rate of interest: ");
    scanf("%f", &rate);
    printf("Enter the time (in years): ");
    scanf("%f", &time);

    interest = (principal * rate * time) / 100;

    printf("Simple Interest: %.2f", interest);

    getch();
}
```

## 3.STAR TRINGAL [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/print_tringal_shap.c)
![Screenshot (53)](https://user-images.githubusercontent.com/117162170/218599468-18a430e7-8d5f-4ea6-bebc-c9db4465cc27.png)
## DIRECT CODE 
star tringal

```bash
 #include<stdio.h>
#include<conio.h>
int main()
{
int n, s, i, j;
clrscr();
printf("Enter number of rows: ");
scanf("%d",&n);
for(i = 1; i <= n; i++)
{
for(s = i; s < n; s++)
printf(" ");
for(j = 1; j <= i; j++)
printf("* ");
printf("\n");
}
getch();
return 0;
}
```

## 4.ONE SIDE STAR PIRAMID  [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/print_one_side_star.c)
![Screenshot (54)](https://user-images.githubusercontent.com/117162170/218599476-24e79e99-5d0d-4f38-839d-5c4be2fbb931.png)
 
 ## DIRECT CODE 
 one side star piramid
```bash
#include <stdio.h>
#include<conio.h>
void main() {
   int i, j, n;
   clrscr();
   printf("Enter the number of rows: ");
   scanf("%d", &n);
   for (i = 1; i <= n; ++i) {
      for (j = 1; j <= i; ++j) {
         printf("* ");
      }
      printf("\n");
   }
getch();
}
```

## 5.NUMERICAL PYRAMID [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/print_numbirical_piramid.c)
![Screenshot (62)](https://user-images.githubusercontent.com/117162170/218600362-71f7bacb-8ac0-4252-8daa-b3d1cfa73387.png)

## DIRECT CODE 
NUMERICAL PYRAMID
```bash
#include <stdio.h>
#include<conio.h>
void main()
{
  int i,j, c=1, n;
  clrscr();
  printf ("enter rows :");
  scanf("%d",&n);
  for(i=1;i<=n;i++)
  {
    for(j=1;j<=i;j++)
    {
      printf("%d",c);
      c++;
    }
    printf("\n");

  }
  getch();
}
```

## 6. POWER OF GIVEN NUBER N [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/power_given_n_number.c)
![Screenshot (55)](https://user-images.githubusercontent.com/117162170/218599537-9c82903c-310d-474b-9de0-5510cfe8a280.png)

## DIRECT CODE 
POWER OF GIVEN NUBER N
```bash
#include <stdio.h>
#include <conio.h>
#include <math.h
void main() {
    int num, power;
    int result;
    clrscr();
    printf("Enter the base number: ");
    scanf("%d", &num);
    
    printf("Enter the exponent: ");
    scanf("%d", &power);
    
    result = pow(num, power);
    
    printf("%d",result);
    
    getch();
}
```

## 7. LUCAS NUMBERS [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/lucas_numbe.c)
![Screenshot (56)](https://user-images.githubusercontent.com/117162170/218599562-ec5d58ee-f24f-4cd3-9e84-c7ef74bb20be.png)

## DIRECT CODE 
LUCAS NUMBERS
```bash

#include<stdio.h>
#include<conio.h>
int main()
{
 int x,y,z,num;
 clrscr();
 printf("Enter the limit of Lucas number : ");
 scanf("%d",&num);
 x=2;
 y=1;
 while(num>=x)
 {
   printf(" %d",x);
   z=x+y;
   x=y;
   y=z;
 }
 getch();

}
```


## 8. FABONIC NUMBERS [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/fabonic_seris.c)
![Screenshot (57)](https://user-images.githubusercontent.com/117162170/218599580-5a8ddef8-d73d-42fe-a63d-6ba97e078ccd.png)

## DIRECT CODE 
FABONIC NUMBERS

```bash
#include <stdio.h>
#include<conio.h>

void main(){

int first=0,second=1,third,i,n;
clrscr();
printf("how many elements : ");
scanf("%d",&n);
// printf("\n%d \n%d",first,second);
for (i=2;i<n;++i)
{
    third=first+second;
    printf("\n%d",third);
    first=second;
    second=third;
}
getch();
}
```


## 9. BIG NUMBER FORM GIVEN TWO NUMBERS [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/compare_big_form_2_numbers.c)
![Screenshot (59)](https://user-images.githubusercontent.com/117162170/218599799-53af43bd-7485-4f7c-9912-1439b124e543.png)


## DIRECT CODE 
 BIG NUMBER FORM GIVEN TWO NUMBERS

```bash
#include <stdio.h>
#include <conio.h>
void main()
{
    int num1, num2;
    clrscr();
    printf("Enter two numbers: ");
    scanf("%d%d", &num1, &num2);

    if (num1 > num2)
        printf("%d is maximum", num1);
    else
        printf("%d is maximum", num2);

    getch();
}
```


## 10. SMALL NUBER FORM GIVEN TWO NUMBERS [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/compare_small_given_2_numbers.c)
![Screenshot (58)](https://user-images.githubusercontent.com/117162170/218599763-a0b252c5-c24b-403c-ac77-8a6faf24ce92.png)

## DIRECT CODE 

SMALL NUBER FORM GIVEN TWO NUMBERS 

```bash
#include <stdio.h>
#include <conio.h>
void main()
{
    int num1, num2;
    clrscr();
    printf("Enter two numbers: ");
    scanf("%d%d", &num1, &num2);

    if (num1 < num2)
        printf("%d is minimum", num1);
    else
        printf("%d is minimum", num2);

    getch();
}
```

## 11. ADDITION OF GIVEN SERIES [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/add_of_given_serias.c)
  ![Screenshot (61)](https://user-images.githubusercontent.com/117162170/218599810-3ce71369-2288-4362-acc6-7255fa843074.png)
  
  ## DIRECT CODE 
  
   ADDITION OF GIVEN SERIES
  
  ```bash
#include<stdio.h>
#include<conio.h>
void main() {
	int n,i;
	int sum=0;
    clrscr();
	printf("Enter the max values of series: ");
	scanf("%d",&n);
	sum = (n * (n + 1)) / 2;
	printf("Sum of the series: ");
	for (i =1;i <= n;i++) {
		if (i!=n)
		             printf("%d + ",i); else
		             printf("%d = %d ",i,sum);
	}
	getch();
}
```
  
  ## 12. BIG NUMBER FORM GIVEN 3 NUMBERS [CODE](https://github.com/GuruMukhPrajapati/1ST_YEAR_C_laguage_CODES/blob/main/PRATICAL_ANSWER_OF_C_PROGRAMMING/comapre_big_form_3_numbers.c)
  ![Screenshot (60)](https://user-images.githubusercontent.com/117162170/218608432-434606d8-0946-48d4-b2d8-b97406400d09.png)
  
  ## DIRECT CODE 
  
  BIG NUMBER FORM GIVEN 3 NUMBERS
  
  ```bash
#include <stdio.h>
#include <conio.h>
void main() {
    int num1, num2, num3;
    clrscr();
    printf("Enter three integers: ");
    scanf("%d%d%d", &num1, &num2, &num3);
    if (num1 > num2 && num1 > num3) {
        printf("%d is the largest number\n", num1);
    } else if (num2 > num1 && num2 > num3) {
        printf("%d is the largest number\n", num2);
    } else {
        printf("%d is the largest number\n", num3);
    }
     getch();
}
```
  

  
  ## FAQ

#### Question 1 where is remaing questions ? 

Answer 1 they will update with your course. some topic are not to be covered by dear sir so i am not able to post them. it will automaic update 



                        



