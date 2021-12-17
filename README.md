#include <iostream>

using namespace std;
//Fahrur Rozi
//30602100020
int main()
{
    int pilihan;
    int i,p;
    cout << "\t\t----- Menu pilihan soal ------\n";
    cout << "\t[1] munculkan bilangan ganjil dan genap kurang dari 50\n";
    cout << "\t[2] munculkan bilangan habis dibagi  \n";
    cout << "\t===============:====================:===============\n\n";
    cout << " \tSilahkan memilih soal\t\t : " ; cin >> pilihan;
    cout << "\t--------------:---------------------------------:-------------------\n";

    switch (pilihan) {
case 1:
    cout << "\n\t***** Bilangan Ganjil dan Genap *****\n ";
    cout << "\t=============================================\n";
    cout << "\t\tBilangan Ganjil\n";
    cout << "\t\t^^^^^^^^\n\t";
    for (i=1;i<=50;i++) {
        if (i%2==1) {
            cout <<i; cout <<", ";}
    }
    cout << "\n\t_________________________________________________________________________________________________\n";
    cout << "\n\t\tBilangan genap\n";
    cout << "\t\t^^^^^^^^\n\t";
    for (i=1;i<=50;i++) {
        if (i%2==0) {
            cout <<i; cout <<", ";}
    }
    cout << "\n\t_________________________________________________________________________________________________\n";
    cout << "\n\n";
    break;
case 2:
    cout << " \n\t Bilangan 1 sampai 200 \n ";
    cout << "\t***** Habis dibagi  ***** \n";
    cout << "\tbilangan pembagi\t : ";
    cin>>p; cout <<"\n";
    cout << "\t=============================================\n\t";
    for (i=1;i<=200;i++) {
        if (i%p==0) {
            cout <<i; cout <<", ";}
    }
    cout << "\n\t___________________________________________________________________\n";
    break;
    }

}

