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
