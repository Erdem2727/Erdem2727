#include <iostream>

int main()
{
    int sayi1;
    int sayi2;

    using namespace std; // using bildirimi ekleyerek std ad alanını kullanabilirsiniz

    cout<<"2 tane sayi giriniz"<<endl;
    cin>>sayi1>>sayi2;

    int puanortalamasi = ((sayi1+sayi2)/2);



    if(puanortalamasi >= 50)
    {
        cout<<"Sinifi gectiniz :)"<<endl;
    }
    else if (puanortalamasi <= 50)
    {
        cout<<"Sinifta kaldiniz :("<<endl;
    }
   
}

   
