# calulator1
Function of caluclator
#include<iostream> 
#include<math.h> 
using namespace std; 
int main () 
{ 
float r,b,PI; 
int cube,z,S;
cout<<"\t\t\t\t\t\t CAlCULATOR \n";
cout<<"------------------------------------------------------------------------------------\n"<<endl;
cout<<"Operations\t\t"<<"\tTrigonometric Functions"<<"\t\tLogarithmic Functions\n"; 
cout<<"------------------------------------------------------------------------------------\n"; 
cout<<"1: ADDITIOM"<<"\t\t6:Sin\t\t"<<"\t\t12: Log"<<endl; 
cout<<"2: SUBTRACTION"<<"\t\t7:Cos"<<"\t\t\t\t13: Log with base 10"<<endl;
cout<<"3: MULTIPLICATION"<<"\t8: Tan"<<"\t\t\t\t14: power"<<endl;
cout<<"4: DIVISION\t\t"<<"9: Inverse of Sin"<<"\t\t15: percentage"<<endl;
cout<<"5:Square root\t\t"<<"10: Inverse of Cos\t\t"<<endl;
cout<<"\t\t\t11: Inverse of Tan"<<"\t\t16 avr"<<endl; 
cout<<"\t\t\t\t\t\t\t17: cube"<<endl; 
cout<<"Enter the function that you want to perform : "; 
cin>>S; 
PI=3.14159265; 
switch(S) 
{ 
case 1: 
cout<<"Enter 1st number : "; 
cin>>r; 
cout<<"Enter 2nd number : "; 
cin>>b; 
cout<<"Addition = "<<r+b<<endl; 
break;
case 2: 
cout<<"Enter 1st number : "; 
cin>>r; 
cout<<"Enter 2nd number : "; 
cin>>b; 
cout<<"Subtraction = "<<r-b<<endl; 
break;  
case 3: 
cout<<"Enter 1st number : "; 
cin>>r; 
cout<<"Enter 2nd number : "; 
cin>>b; 
cout<<"Multiplication = "<<r*b<<endl; 
break; 
case 4: 
cout<<"Enter 1st number : "; 
cin>>r; 
cout<<"Enter 2nd number : "; 
cin>>b; 
cout<<"Division = "<<r/b<<endl; 
break;
case 5: 
cout<<"Enter the number : "; 
cin>>r; 
cout<<"Square Root = "<<sqrt(r)<<endl; 
break; 
case 6: 
cout<<"Enter the number : "; 
cin>>r; 
cout<<"Sin = "<<sin(r)<<endl; 
break; 
case 7: 
cout<<"Enter the number : "; 
cin>>r; 
cout<<"Cos = "<<cos(r)<<endl; 
break; 
case 8: 
cout<<"Enter the number : "; 
cin>>r; 
cout<<"Tan = "<<tan(r)<<endl; 
break; 
case 9: 
cout<<"Enter the number : "; 
cin>>r; 
cout<<"Inverse of Sin = "<<asin(r)*180.0/PI<<endl; 
break; 
case 10: 
cout<<"Enter the number : "; 
cin>>r; 
cout<<"Inverse of Cos = "<<acos(r)*180.0/PI<<endl; 
break; 
case 11: 
cout<<"Enter the number : "; 
cin>>r; 
cout<<"Inverse of tan = "<<atan(r)*180.0/PI<<endl; 
break; 
case 12: 
cout<<"Enter the number : "; 
cin>>r; 
cout<<"Log = "<<log(r)<<endl; 
break; 
case 13: 
cout<<"Enter the number : "; 
cin>>r; 
cout<<"Log with base 10 = "<<log10(r)<<endl; 
break; 
case 14:
cout<<"Enter the Number for Calculating its Power: "<<endl;
cout<<"Enter 1st number : "; 
cin>>r; 
cout<<"Enter 2nd number : "; 
cin>>b; 
cout<<"power = "<<pow(r,b)<<endl; 
break;
case 15:
cout<<"Enter the Number for Calculating its percentage: "<<endl;
cout<<"Enter 1st number : "; 
cin>>r; 
cout<<"Enter 2nd number : "; 
cin>>b; 
cout<<"percentage = "<<(r+b)/300*100<<endl; 
break;
case 16:
cout<<"Enter the Number for Calculating its average: "<<endl;
cout<<"Enter 1st number : "; 
cin>>r; 
cout<<"Enter 2nd number : "; 
cin>>b; 
cout<<"Enter 3nd number : "; 
cin>>z; 
cout<<"average = "<<(r+b+z)/3<<endl; 
break;
case 17:
cout<<"Enter the Number for Calculating its cube: "<<endl;
cin>>z;
cube=z*z*z;
cout<<"cube"<<"="<<cube <<endl;
break;
default: 
cout<<"ERROR"<<endl; 

} 
}
