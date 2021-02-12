# Lab-3.30
#include <iostream>
#include <iomanip> 	
using namespace std;

int main()
{
	double totalSales = 1080;		 
	double stateTax = .06;	
	double localTax = .02;	
  
	cout << setprecision(2) << fixed;	
	
	cout << "Please input the total sales for the month\n";
	cin >> totalSales;
   
	cout << "Please input the state tax percentage in decimal form (0.2 for 2%)\n"; 
  cin >> stateTax; 
  
  cout << "Please input the local tax percentage in decimal form (0.2 for 2%)\n";
  cin >> localTax; 
  
	cout << "The total sales for the month is $" << totalSales << endl;
  
  stateTax = 1080 * .06; 
  cout << "The state tax for the month is $" << stateTax << endl;
  
  localTax = 1080 * .02;
  cout << "The local tax for the month is $" << localTax << endl;
  

}
