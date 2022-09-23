# c-program-to-display-the-multiple-table-
#include<iostream>
 using namespace std;
 int main()
 {
     int i , num ;
     cout<<"enter number to print table: ";
     cin >>num;
      for(i = 1 ; i <= 10 ; i++)
 {
    cout << num << "\n* " << i << " \n =" << (num*i) << endl ;
 }
}
