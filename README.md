# Sistema Cliente-Servidor Multihilo en Java

## Descripción
Este proyecto implementa un servidor capaz de atender múltiples clientes simultáneamente mediante el uso de hilos en Java.

Cada cliente se conecta al servidor y es gestionado de manera independiente, permitiendo la concurrencia en las operaciones.

## Características
- Manejo de múltiples clientes simultáneamente
- Uso de Threads para concurrencia
- Comunicación mediante sockets
- Separación entre cliente y servidor

## Estructura del proyecto
- Cliente/: aplicación cliente
- Servidor/: lógica del servidor

## Cómo funciona
El servidor permanece en espera de conexiones entrantes.
Cada vez que un cliente se conecta, se crea un nuevo hilo encargado de gestionar la comunicación con ese cliente.

## Cómo ejecutar
1. Ejecutar el servidor
2. Ejecutar uno o más clientes
