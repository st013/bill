# bill
#include <iostream>
using namespace std;
int main(){
cout<<"WELCOME TO THE FOODMART. \n";
cout<<"What would you like to buy today? \n";
cout<< "Note: Simply put quantity as 0 for items you don't want to buy."<<endl;
cout<<"Strawberry Milkshake - INR 45/- per glass \n Number of glasses :"; //sm
int smcount;
cin >> smcount;
cout<<"Chocolate Milkshake - INR 50/- per glass \n Number of glasses :";//cm
int cmcount;
cin >> cmcount;
cout<<"Brownies - INR 20/- per piece \n Number of pieces :";//b
int bcount;
cin>> bcount;
cout<<"Vanilla Pastry - INR 60/- per piece \n Number of pieces: ";//vp
int vpcount;
cin>> vpcount;
cout<<"Cookies - INR 30/- per piece \n Number of pieces :";//c
int ccount;
cin>> ccount;
cout<<"Fruit Cake - INR 20/- per piece \n Number of pieces :";//fc
int fccount;
cin>>fccount;
cout<< "We are processing your bill. Please press any key to continue."<<endl;
string bill;
cin>> bill;
const int sm=45,cm=50,b=20,vp=60,c=30,fc=20;
int sum;
sum= sm*smcount + cm*cmcount + b*bcount + vp*vpcount + c*ccount +fc*fccount;
cout<<"Your total payable amount is INR "<<sum<<"/-"<<endl;
cout<<"Thanks for shopping. Please visit again.";
  return 0;
}
