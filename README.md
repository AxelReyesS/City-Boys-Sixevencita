#include <iostream>
using namespace std;

int main () {
    
    int op, kg, ton, gr, lbr, onz;
    
    cout<<"Escribe el numero de la opcion que necesitas."<<endl;
    cout<<"1. Kilogramos a Toneladas."<<endl;
    cout<<"2. Kilogramos a Gramos."<<endl;
    cout<<"3. Kilogramos a Libras."<<endl;
    cout<<"4. Kilogramos a Onzas."<<endl;
    cin>>op;

    if (op==1){
        cout<<"Introduce el valor de Kilogramos: ";
        cin>>kg;
        
        ton= kg/1000;
        
        cout<<"Loa Kilogramos convertidos a Toneladas son: "<<ton;

    } else {
        cout<<"Escribiste opcion invalida";
    }

    return 0;
}
