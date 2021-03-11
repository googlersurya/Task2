//program to check eligiblity of employee to apply to this job
#include<iostream>
using namespace std;
int main()
{
	//let ex be the experience and no be number of individual projects made by the employee
	int ex,no;
	cout<<"Enter your work experience:";
	cin>>ex;
	if(ex>=3)
	{
	    cout<<"Enter no of projects made by you:";
		cin>>no;
		if(no>50)
	    {
		cout<<"You are eligible to apply\n";
	    }
	    else
	    {
		cout<<"You need more experirence\n";
	    }
    }
	else
	{
	    cout<<"You are not eligible to apply\n";
    }
    return 0;
}

