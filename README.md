# week-5-assignment

#include <iostream> using namespace std;
void findLargest(double &a, double &b, double &c, double &largest) {     largest = a;     if (b > largest)         largest = b;     if (c > largest)         largest = c; }
int main() {     double x = 1.25, y = 0.75, z = 2.50, result;     findLargest(x, y, z, result);     cout << "Largest fraction: " << result << endl;     return 0;
}
