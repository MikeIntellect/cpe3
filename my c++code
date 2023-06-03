#include <iostream>
#include <cmath>


using namespace std;

int banner();
void input_parameter(int value, float* var1_ptr, float*var2_ptr, float*var3_ptr);
float analysis(int value,float* var1_ptr, float*var2_ptr, float*var3_ptr );

int main()
{
	float result,var1,var2, var3;
int choice;
	choice = banner();
input_parameter(choice,&var1,&var2,&var3);
result = analysis(choice,&var1,&var2,&var3);
system ("pause");
return 0;
}

/* calling function*/
int banner()
{
	int choice;

	cout<< "Welcome to the Equation of Motion Application Programme"<<endl;
	cout << "1. fisrt equation: s=u*t + (1/2)*a*t^2'"<<endl;
	cout << "2. Second equation: v = u + a*t," <<endl;
	cout << "3. Third equation: v^2 = u^2 + 2*a*s"<<endl;
	cout << " Choice the Equation to Solve =>"<<endl;
	cin >>choice;
	return choice;
}

//calling function
void input_parameter(int value, float* var1_ptr, float*var2_ptr, float*var3_ptr)

{

if (value == 1){
cout <<"enter the values of: u , t , a "<<endl;
cin>>*var1_ptr >>*var2_ptr>>*var3_ptr;
}
else if(value == 2)

{
	cout<<" enter the values of: u, a ,t \n";
	cin >> *var1_ptr>>*var2_ptr>>*var3_ptr;
}

else if(value==3)
{
	cout<<"enter the values of:  u, a, s \n";
	cin>>*var1_ptr>>*var2_ptr>>*var3_ptr;
	
}
}
//callling function
float analysis(int value,float* var1_ptr, float*var2_ptr, float*var3_ptr )

{
	
double s,v;
switch (value)
 {
case 1:
s=(*var1_ptr* *var3_ptr) +( 0.5) * ((*var2_ptr) * (pow(*var3_ptr, 2)));
	return s;
case 2:
	v= (*var1_ptr) + ((*var2_ptr) * (*var3_ptr));
	return v;

case 3:
	v = sqrt( pow((*var1_ptr),2) + (2 * (*var2_ptr) *(*var3_ptr)));
	return v;
default:
	return -1;
}
}

