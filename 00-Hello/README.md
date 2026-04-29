# Trabajo Práctico 00 - Hello

##  Autor

- Usuario GitHub: LOlivastri-FRBa
- Legajo: 209.118-5
- Apellido: Olivastri
- Nombre: Lautaro

##  Enunciado

Programa simple de prueba.

##  Hipótesis

Se busca verificar el correcto funcionamiento del entorno de desarrollo.

##  Resolución

Se implementó MYSY2 en C++ que imprime por consola el mensaje "Hola mundo".

Para compilar:
g++ hello.cpp -o hola

Para ejecutar:
./hola

### Código:

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hola mundo" << endl;
    return 0;
}
