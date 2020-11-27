#include<iostream>
using namespace std ;
int main ()
{
	int age , temp = 0 ;
	
	cout<<"\nenter your age here: " ;
	cin>>age ;
	
	if( age>=18 && age<100 ) 
	{
	cout<<" Congratulation !!!  you Are Eligible For Voting " ;
	} 
	
	else if ( age >= 100 ) 
	{
	cout<<" You Are Eligible But We Suggest Take a Rest " ;
    }
    
    else if ( age < 18 )
    {
    	temp = 18 - age ;
    	cout<<" you Are Not Eligible or You Are Not Mature " ;
    	cout<<"Wait " << temp <<" Years For Vote " ;
	  }
}
