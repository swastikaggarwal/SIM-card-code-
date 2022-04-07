// SIM-card-code-// 
#include<stdio.h>
int main(){
int amt;
char sim,press;
printf("Enter your sim card Artel or Vodafone");
printf("\npress A for airtel and V for vodafone : ");
scanf("%c",&sim);
if(sim=='A'|| sim=='a')
{
 
 printf("\n\n******4G Tariff plan are given below*******");
 
 printf("\n\n           *******Aitel******");
 
 printf("\n|                     |  100Rs   |  300Rs  |  500Rs |  800Rs |");
 
 printf("\n|Data/Day             |  500MB   |  1.2GB  |   2GB  |   3GB  |");
 
 printf("\n|Talk Time (in min)   |   100    |   200   |   300  |   400  |");
 
 printf("\n|Validity(in days)    |   60     |   98    |   180  |   250  |");
 
 printf("\n|SMS (per day)        |   100    |   200   |   300  |   400  |");
 
 printf("\n\nEnter the amount : Rs");
 
 scanf("%d",&amt);
 
 printf("if you want to recharge your sim press Y and for exit press N:");
 
 scanf(" %c",&press);
 
 if(press=='y'||press=='Y')
 
 { switch(amt)
   {
    case 100:
    
    printf("\nYour sim is successfully recharged with amount Rs100. You will get");
    
    printf("\nfollowing facilities with Airtel :-");
    
    printf("\n*500MB 4G data per day");
    
    printf("\n*Talk Time 100 minutes");
    
    printf("\n*100 SMS per day");
    
    printf("\n*Valid for 60 days");
    break;

    case 300:
    
    printf("\nYour sim is successfully recharged with amount Rs300. You will get");
    
    printf("\nfollowing facilities with Airtel :-");
    
    printf("\n*1.2Gb 4G data per day");
    
    printf("\n*Talk Time 200 minutes");
    
    printf("\n*200 SMS per day");
    
    printf("\n*Valid for 98 days");
    break;

    case 500:
    
    printf("\nYour sim is successfully recharged with amount Rs500. You will get");
    
    printf("\nfollowing facilities with Airtel :-");
    
    printf("\n*2GB 4G data per day");
    
    printf("\n*Talk Time 300 minutes");
    
    printf("\n*300 SMS per day");
    
    printf("\n*Valid for 180 days");
    break;

    case 800:
    
    printf("\nYour sim is successfully recharged with amount Rs800. You will get");
    
    printf("\nfollowing facilities with Airtel :-");
    
    printf("\n*3GB 4G data per day");
    
    printf("\n*Talk Time 400 minutes");
    
    printf("\n*400 SMS per day");
    
    printf("\n*Valid for 250 days");
    
    break;
    default:
    printf("You enter wrong amount. Try again.");
   }
 }
 
 else
  {
    printf("\nThanks for coming");
  }

}
else if( sim=='v'|| sim=='V')
{
 
 printf("\n\n******4G Tariff plan are given below*******");
 
 printf("\n\n           *******Vodafone******");
 
 printf("\n|                     |  100Rs   |  300Rs  |  500Rs |  800Rs |");
 
 printf("\n|Data/Day             |  500MB   |  1.2GB  | 2.2GB  |  3.5GB |");
 
 printf("\n|Talk Time (in min)   |   110    |   210   |   330  |   410  |");
 
 printf("\n|Validity(in days)    |   64     |   100   |   185  |   253  |");
 
 printf("\n|SMS (per day)        |   100    |   200   |   300  |   400  |");
 
 printf("\n\nEnter the amount : Rs");
 
 scanf("%d",&amt);
 
 printf("if you want to recharge your sim press Y and for exit press N:");
 
 scanf(" %c",&press);
 if(press=='y'||press=='Y')
 { switch(amt)
   {
    case 100:
    
    printf("\nYour sim is successfully recharged with amount Rs100. You will get");
    
    printf("\nfollowing facilities with Airtel :-");
    
    printf("\n*500MB 4G data per day");
    
    printf("\n*Talk Time 110 minutes");
    
    printf("\n*100 SMS per day");
    
    printf("\n*Valid for 64 days");
    
    break;

    case 300:
    printf("\nYour sim is successfully recharged with amount Rs300. You will get");
    
    printf("\nfollowing facilities with Airtel :-");
    
    printf("\n*1.2Gb 4G data per day");
    
    printf("\n*Talk Time 210 minutes");
    
    printf("\n*200 SMS per day");
    
    printf("\n*Valid for 100 days");
    
    break;

    case 350:
    
    printf("\nYour sim is successfully recharged with amount Rs500. You will get");
    
    printf("\nfollowing facilities with Airtel :-");
    
    printf("\n*2.2GB 4G data per day");
    
    printf("\n*Talk Time 330 minutes");
    
    printf("\n*300 SMS per day");
    
    printf("\n*Valid for 185 days");
    
    break;

    
    
    printf("\nYour sim is successfully recharged with amount Rs800. You will get");
    
    printf("\nfollowing facilities with Airtel :-");
    
    printf("\n*3.5GB 4G data per day");
    
    printf("\n*Talk Time 410 minutes");
    
    printf("\n*400 SMS per day");
    
    
    
    break;
    default:
    printf("You enter wrong amount. Try again.");
   }
 }
 
 


}

else
{
  printf("\nYou press wrong button. Thanks for coming.");
}

return 0;
