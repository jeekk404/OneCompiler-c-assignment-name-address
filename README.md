#include <iostream>
using namespace std;
int main() {
	//blok deklarasi
	string nama, alamat, hobi;
	
	//blok input
	cout<<"Masukan nama anda:";
	getline(cin,nama);
	cout<<"Masukan alamat anda: ";
	getline(cin,alamat);
	cout<<"Masukan hobi       : ";
	getline(cin,hobi);
	
	//blok output
	cout<<"\n\n";
	cout<<"====================================="<<endl;
	cout<<"             DATA MAHASISWA          "<<endl;
	cout<<"====================================="<<endl;
	cout<<"Nama Lengkap   : "<< nama <<endl;
	cout<<"Alamat Lengkap : "<< alamat <<endl;
	cout<<"Hobi Saya      : "<< hobi <<endl;
	cout<<"====================================="<<endl;
	cout<<"\n\n";
	return 0;
}
