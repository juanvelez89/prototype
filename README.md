# prototype
Este es el ejemplo práctico del patrón de diseño prototype en c# y una corta explicación para entender en lo que consiste. 

Basado en el libro:
#### Design Patterns Elements of reusable Object-Oriented Software de Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides.

## Definición
Es un patrón de diseño creacional el cual especifica el tipo de objetos para crear usando una instancia prototipica y crear los nuevos objetos copiando este prototipo.

## Aplicabilidad


## Participantes en el patrón

### Prototype
Declara una interfaz para clonarse a si misma.

### ConcretePrototype
implementa la operacion de prototype para clonarse a si misma.

### Client
crea un nuevo objeto preguntando un prototipo para clonar.
