# movie-ticket-booking-
Movie Booking system
#include<stdio.h>

#include<stdlib.h>

#include<stdarg.h>

int main ()

{

printf("*******welcome  to BG MOVIE website*******");

 char arr[30];

printf("\nEnter your name : "); scanf("%s",arr);

printf("\nhello %s ,welcome to our website ", arr); int x;

printf("\nEnter a number to select your movie?\t 1)Avatar\t 2)veera simha reddy\t 3)Spider Man\t 4)black adam \t");

scanf("%d", &x); switch(x)

{

case 1:

printf("you have selected **avatar movie** "); break;

 

case 2:

printf("you have selected **veera simha reddy** "); break;

 

case 3:

printf("you have selected **Spider Man** "); break;

 

case 4:

printf("you have selected **black adam** "); break;

 

}

int a,b;

printf("\nplease select your area ?1)chennai\t 2)delhi\t 3)mumbai\t 4)hyderbad \t"); scanf("%d",&a);

 

switch(a)


{


case 1:

printf("welcome to BG movies box office in chennai"); break;

case 2:

printf("welcome to BG movies box office in delhi"); break;

case 3:

printf("welcome to BG movies box office in mumbai"); break;

case 4:

printf("welcome to BG movies box office in hyderabad"); break;

 }

 int c,d,amount;

printf("\nselect your movie type ?\t1)2D\t 2)3D \t"); scanf("%d",&c);

 

if(c==1){

printf("you have selected 2D picture");

}

else if(c==2)

{

printf("you have selected 3D picture");

}

printf("\nplease select your type of site?\t 1)chair\t2)balcony\t 3)sofa\t "); scanf("%d",&d);

if(d==1)

{


printf("you have selected chair type seats and cost is 100 Rs per seat ");


}

else if(d==2)


{


printf("you have selected balcony seats and cost is 150 Rs per seat ");


}


else if(d==3)

 

{

 

printf("you have selected sofa and cost is 250 Rs per person ");

 

}

printf("\n%s please enter how many tickets do you want ? ",arr); scanf("%d",&b);

 

if(c==1&&d==1)

{printf("\nyou have selected 2D picture**cost is 50 charge and chair seat charge is 100 \n");

 

amount=(50+100)*b;

 

printf("total amount to be paid  :%d",amount);

 

}

 

else if(c==1&&d==2)

 

{

printf("\nyou have selected 2D picture**cost is 50 charge and balcony seat charge is 150 \n "); amount=(50+150)*b;

printf("total amount to be paid :%d",amount);

 

}

 

else if(c==1&&d==3)

 

{

printf("\nyou have selected 2D picture**cost is 50 charge and sofa seat charge is 250 \n "); amount=(50+250)*b;

printf("total amount to be paid :%d",amount);

 

}

 

else if(c==2&&d==1)

{  printf("\nyou have selected 3D picture**cost is 100 charge and chair seat charge is 100 \n"); amount=(100+100)*b;

 

printf("total amount to be paid :%d",amount);

 

}

 

else if(c==2&&d==2)

 

{

 

printf("\nyou have selected 3D picture**cost is 100 charge and balcony seat charge is 150\n");

amount=(100+150)*b;

 

printf("total amount to be paid :%d",amount);

 

}

 

else if(c==2&&d==3)

 

{

printf("\nyou have selected 3D picture**cost is 100 charge and sofa seat charge is 250\n"); amount=(100+250)*b;

 

printf("total amount to be paid :%d",amount);

 

}

int w;

printf("payment method you wish for\t1)cash\t2)online payment\n");

scanf("%d", &w); switch(w)

 

{

 

case 1:

printf("you have selected **cash payment** ");

printf("\nyou have successfully paid the amount%d Rs",amount);

printf("\n enjoy your show");

printf("\nThank you !! please follow our BG movies website seats allocted before movie");

break;

 

case 2:

printf("you have selected **Online payment** ");

printf("\nplease pay the amount to this number +91 89-2143-6325 "); int g;

printf("\nplease Enter your otp:");

scanf("%d",&g);

 

 

if(g==123456)

{

 

printf("\nyou have successfully paid the amount%d Rs",amount);

printf("\n enjoy your show");

printf("\nThank you !! please follow our BG movies website seats allocted before movie");

 

}

else

 

{

 

printf("our transction is failed please try again");

break;

}}

 

printf("\n*******Thank you for using our BG movies website*******");}
