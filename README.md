# Task-2-CP-Lab-open-eded-1
#include<iostream>
using namespace std;
int main(){
int num,count=0,i;
cout<<"Check whether a number is prime or not\n";
cout<<"Enter a range\n";
cin>>num;
for(i=2;i<=num;i++){
 if(num%i==0){
 count=count+1; 
if (count==1)
    cout<<"Number is prime\n";
else
cout<<"Not prime\n";
}
cout<<"Done";
}
return 0;

}
