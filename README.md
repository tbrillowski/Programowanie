=======


#include <iostream>

int main ()
{
int x=0, y, n=0, suma=0;
cout<<"Podaj ilosc liczb ktore chcesz zsumowac"<<endl;
cin>>x;
cout<<"Podaj liczby ktore chcesz zsumowac"<<endl;
for (y=0, y<x;y++)
  {
    cin>>n;
    suma=suma+n;
  }
cout<<"Suma podanych liczb wynosi: "<<suma<<;
return 0;
}
