//// metodo de busqueda secuencial o lineal.

//// busqueda secuencial o lineal

/// creamos un arreglo 
//a[5]={3,4,2,1,5}; dato = 4;

#include <iostream>
#include <conio.h>

using namespace std;

int main(){
 int a[] = {3,4,2,1,5};
 int i,dato;
 char band ='f';
 
 dato = 4;
 /// busqueda lineal
 
 i=0
 while((band == 'f') && (i<5) ){
    if (a[i] == dato){
        band = 'v';
    }
    i++;
 }
  
  if(band == 'f'){
      cout<<"el numero no existe en el arreglo"<<end1;
  }
  else if (band == 'v'){
      cout<<"el numero a sido encontrado en la posicion :"<<i-1<<end1;
  }
 getch();
 return 0;
}
