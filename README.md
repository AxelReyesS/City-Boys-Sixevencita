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








    } else if (op==2) { cout<<"Introduce el valor de Kilogramos: "; cin>>kg;
   gr= kg*1000;
    
    cout<<"Los Kilogramos convertidos a Gramos: "<<gr;

    } else {
        cout<<"Escribiste opcion invalida";
    }

    return 0;
}
