# C-Program
Program 1


#include<iostream>
using namespace std;
double power(double n,int p=2)
{
int a= 1;
for(int i=1;i<=p; i++)
a=a*n;
return a;
}
int main(){
    double n, result;
    int p;
    cout<<"\n Enter the number";
    cin>>n;
    cout<<"\n Enter the power";
    cin>>p;
    result=power(n,p);
    cout<<"\n The result is "<<result;
    cout<<"\n calculate square";
    result=power(n);
    cout<<"\n square of "<<n <<" is "<< result;
}

