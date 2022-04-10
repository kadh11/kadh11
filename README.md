- 👋 Hi, I’m @kadh11
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
kadh11/kadh11 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <iostream>
#include <cmath>
using namespace std;
double A (double Toan, double NN, double Ly, double Hoa, double TH)
{
    return (Toan*2+NN*2+Ly+Hoa+TH)/7;
}
double B (double Toan, double Hoa, double Sinh)
{
    return (Toan*2+Sinh+Hoa)/4;
}
double C (double Van, double Su, double Dia)
{
    return (Van*2+Dia+Su)/4;
}
double KNM (double NN, double TH, double TD)
{
    return (NN*2+TH+TD)/4;
}

int main()
{
   double Toan, Ly, Hoa, NN, Van, Su, Dia, TH, TD, Sinh, A, B, C, KNM;
   cout<<"Nhap Toan: ";
   cin>>Toan;
   cout<<"Nhap Ly: ";
   cin>>Ly;
   cout<<"Nhap Hoa: ";
   cin>>Hoa;
   cout<<"Nhap Van: ";
   cin>>Van;
   cout<<"Nhap NN: ";
   cin>>NN;
   cout<<"Nhap Su: ";
   cin>>Su;
   cout<<"Nhap Sinh: ";
   cin>>Sinh;
   cout<<"Nhap Dia: ";
   cin>>Dia;
   cout<<"Nhap TH: ";
   cin>>TH;
   cout<<"Nhap TD: ";
   cin>>TD;
   double (Toan*2+NN*2+Ly+Hoa+TH)/7;
   double (Toan*2+Hoa+Sinh)/4;
   double (Van*2+Dia+Su)/4;
   double (NN*2+TD+TH)/4;
   cout<<"Band A: "<<(Toan*2+NN*2+Ly+Hoa+TH)/7<<endl;
   cout<<"Band B: "<<(Toan*2+Hoa+Sinh)/4<<endl;
   cout<<"Band C: "<<(Van*2+Su+Dia)/4<<endl;
   cout<<"Band KNM: "<<(NN*2+TH+TD)/4<<endl;
   
    return 0;
}
