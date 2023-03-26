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




