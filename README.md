# loops-in-c-
Questions of loops in c++



// Loops started

// table of 19
#include<iostream>
using namespace std;
int main(){
    
    for(int i=1;i<=10;i++)
    {
        cout<<"19 <<i*19<<endl;
    }
}



// Display this AP 100,97,94,91, upto n terms..

#include<iostream>
using namespace std;
int main()
{
    
    for(int i=100;i>=1;i-=3){
        cout<<i<<endl;;
    }
}



// Display this AP 1,3,5,7 upto n terms..

#include<iostream>
using namespace std;
int main()
{
    int n;
    cout<<"enter the number..";
    cin>>n;
    for(int i=1;i<=n;i+=2){
        cout<<i<<endl;;
    }
}


//Print all the odd number from 1 to 100

#include<iostream>
using namespace std;
int main(){
    
    for(int i=1;i<=100;i+=2)
    {
        cout<<i<<endl;
    }
}


//Print number from 1 to 100 that are divisible by 3

#include<iostream>
using namespace std;
int main()
{
    for(int i=1;i<=100;i++)
    {
        if(i%3==0){
            cout<<i<<endl;;
        }
        
    }
}



// print the table of 'n' here n is an interger which the user will input..

#include<iostream>
using namespace std;
int main()
{
    int  n;
    cout<<"enter the number ";
    cin>>n;
    for(int i=1;i<=10;i++)
    {
        cout<<"table of number is."<<n*i<<endl;
    }
}


//Display this AP 4,7,10,13,16.....n upto n terms 

#include<iostream>
using namespace std;
int main()
{
    int n;
    cout<<"enter the number = ";
    cin>>n;
    for(int i=4;i<=n;i+=3){
        cout<<"given AP for number is   "<<i<<endl;
        
    }
}


//Display this GP - 3,12,48,.. upto ‘n’ terms.

#include<iostream>
using namespace std;
int main()
{
    int n;
    cout<<"enter the number..";
    cin>>n;
    for(int i=3;i<=n;i*=4){
        cout<<"GP is  "<<i<<endl;
    }
}




