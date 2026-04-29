# Trabajo Práctico 00 - Hello

##  Autor

- Usuario GitHub: LOlivastri-FRBa
- Legajo: 209.118-5
- Apellido: Olivastri
- Nombre: Lautaro

##  Enunciado

Programa simple de prueba.
 
##  Resolución

Se implementó MYSY2 en C++ que imprime por consola el mensaje "Hola mundo".

Para compilar:
g++ hello.cpp -o hola

Para ejecutar:
./hola

### Código:

```cpp
#include <iostream>

int main() {
    std::cout << "Hola mundo" << std::endl;
    std::cout << "Nombre y apellido: Lautaro Olivastri" << std::endl;
    std::cout << "Curso: K1053" << std::endl;
    std::cout << "Grupo: 5 " << std::endl;

    return 0;
}
