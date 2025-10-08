# week7_lab
#include <iostream>
using namespace std;
//problem6

// double caltotal(double price, int tickets) {
//     return price * tickets;
// }
//
// int main() {
//     int choice, tickets;
//     double total;
//     char option;
//
//     do {
//         cout << "Movie A - $8" << endl;
//         cout << "Movie B - $10" << endl;
//         cout << "Movie C - $12" << endl;
//         cout << "Select an option (1-3): ";
//         cin >> choice;
//
//         cout << "Enter number of tickets: ";
//         cin >> tickets;
//
//         switch (choice) {
//             case 1:
//                 total = caltotal(8.0, tickets);
//                 cout << "Total is $" << total << endl;
//                 break;
//             case 2:
//                 total = caltotal(10.0, tickets);
//                 cout << "Total is $" << total << endl;
//                 break;
//             case 3:
//                 total = caltotal(12.0, tickets);
//                 cout << "Total is $" << total << endl;
//                 break;
//             default:
//                 cout << "Wrong choice!" << endl;
//                 break;
//         }
//
//         cout << "\nDo you want to continue? (y/n): ";
//         cin >> option;
//         cout << endl;
//
//     } while (option == 'y' || option == 'Y');
//
//     cout << "Thank you!" << endl;
//
//     return 0;
// }
//problem7
// double parkingfee(int hours) {
//     double fee = 0;
//
//     if (hours<=2) {
//         fee=0;
//     }else if (hours<=5) {
//         fee=(hours-2)*2;
//     }else {
//         fee=(3*2)+(hours-5)*5;
//     }
//     return fee;
// }
//
//
// int main() {
//     int hours;
//     char again;
//     while(true) {
//         cout<<"enter hours: ";
//         cin>>hours;
//         double fee=parkingfee(hours);
//         cout<<"fee: "<<fee<<endl;
//         cout<<"do you want to use any user ";
//         cin>>again;
//         if(again!='y' || again!='Y') {
//             break;
//
//         }
//         cout<<endl;
//     }return 0;
//
//
//
//
// }
//problem8
// double orderSystem(double price, int items) {
//     return price * items;
// }
//
// int main() {
//
//     int choice, items;
//     double total;
//     char option;
//
//     do {
//         cout<<"pizza - $10"<<endl;
//         cout<<"burger - $8"<<endl;
//         cout<<"salad - $5"<<endl;
//         cout<<"select an option (1-3)"<<endl;
//         cin>>choice;
//
//         cout<<"enter numbers of items: "<<endl;
//         cin>>items;
//
//         switch(choice) {
//             case 1:
//                 total = orderSystem(10, items);
//                 cout<<"total price: "<<total<<endl;
//                 break;
//             case 2:
//                 total = orderSystem(8, items);
//                 cout<<"total price: "<<total<<endl;
//                 break;
//             case 3:
//                 total = orderSystem(5, items);
//                 cout<<"total price: "<<total<<endl;
//                 break;
//             default:
//                 cout<<"wrong choice"<<endl;
//                 break;
//         }
//         cout << "\nDo you want to continue? (y/n): ";
//         cin>>option;
//         cout << endl;
//
//
//     }while (option == 'y' || option == 'Y');
//
//     cout << "Thank you!" << endl;
//
//     return 0;
//
// }
