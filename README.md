# Introduction-to-Software-Engineering
//Học tập
// Nhap bon so in ra so co gia tri lon nhat 
#include <iostream>
using namespace std;
int main () { 
   int a, b, c, d, max;
   cout << "enter the number a : ";
   cin >> a;
   cout << "enter the number b : ";
   cin >> b;
   cout << "enter the number c : ";
   cin >> c;
   cout << "enter the number d : ";
   cin >> d;
   max = a;
   if ( b > max ) max = b;
   if ( c > max ) max = c;
   if ( d > max ) max = d;
   cout << "The largest number is : " << max << endl;
   return 0;
   
}
