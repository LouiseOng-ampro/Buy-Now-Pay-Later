# Buy-Now-Pay-Later
#include <iostream>
#include <iomanip>
#include <vector>
#include <string>
using namespace std;



   int main() {
   double rates[4] = {0.0, 1.5, 2.0, 3.0};
   int terms[4] = {3, 6, 9, 12};
   cout << "=== BNPL Calculator ===\n\n";

   double amount;
   cout << "Purchase amount: RM ";
   cin >> amount;

   if (amount <= 0) {
   cout << "that's not a real amount, try again later\n";
   return 1;
   }

   cout << "\nPick a plan:\n";
    cout << "1) 3 months, no interest\n";
    cout << "2) 6 months, 1.5% interest\n";
    cout << "3) 9 months, 2% interest\n";
    cout << "4) 12 months, 3% interest\n";
    cout << "> ";

    int choice;
    cin >> choice;

