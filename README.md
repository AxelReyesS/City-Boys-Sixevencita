# City-Boys-Sixevencita
Programa para convertir kilogramos a otras medidas de peso
#include <iostream>
using namespace std;

int kg;
float Libras;

int main()
{
    cout<<"Introduce el numero de kilogramos que se van a convertir: ";
    cin>>kg;
    
    Libras=kg*2.2046;
    
    cout<<"El resultado en libras es: "<<Libras;

    return 0;
}
