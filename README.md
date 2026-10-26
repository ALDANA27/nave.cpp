# Proyecto Final: Consola de la Nave

Proyecto de Fundamentos de Programación 2026, hecho en C++ y en modo texto.

## Descripción

La nave está en reentrada atmosférica y gasta demasiada energía. Si no se optimizan los recursos, los motores no tendrán potencia para frenar al tocar tierra. El usuario  tiene que apagar sistemas que no son necesarios antes de empezar el descenso.

## Sistemas de la nave

Sistemas que se pueden apagar:
- Luces de cabina
- Clima secundario
- Radar de investigación

Sistemas vitales (no se deben apagar):
- Ordenador de navegación
- Retro-propulsores

## Posibles finales

1. Si se apaga un sistema vital, la nave pierde el control o se estrella.
2. Si no se apagan suficientes sistemas secundarios, se acaba la energía antes de aterrizar.
3. Si se apagan solo sistemas secundarios y los vitales siguen encendidos, el aterrizaje es perfecto.

## Qué hara el programa

- Pide usuario y clave al iniciar (login), con dos tipos de usuario: comandante e ingeniero.
- Tiene un menú principal con opciones distintas según el tipo de usuario.
- Permite registrar tripulantes y ver la lista de los que ya están registrados.
- El comandante apaga o enciende sistemas de la nave y simula el descenso de 5 fases.
- Al final muestra si el aterrizaje fue perfecto o por qué falló la nave.
- Muestra un reporte sencillo con cuántas misiones salieron bien y cuántas mal.
- Tiene una opción de ayuda y otra con los integrantes del grupo.

## Estructuras que usaremos 

- `const`: valores fijos como el costo de energía y las 5 fases
- `do-while`: para que el menú se repita
- `switch-case`: para elegir el sistema del menú
- `while`: para validar las opciones
- `for`: para recorrer las fases del descenso
- `if / else if / else`: para decidir el final

## Cómo ejecutarlo

```
g++ nave.cpp -o nave
./nave
```

## Integrantes

- Carlos Anderson Aldana Rivas :00018226
- Alessandro Enmanuel Barquero Lopez :00401421

