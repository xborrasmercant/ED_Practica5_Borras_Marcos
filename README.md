# Práctica 5
## Xavier Borrás Mercant y Miguel Marcos Nazco

### Creación del proyecto, paquete e interfaz ICalculadora.
Empezamos la práctica creando el proyecto (*hemos usado Eclipse IDE*).
A continuación, creamos el paquete en conjunto con la interfaz *ICalculadora* y escribimos los métodos para luego implementarlos en la clase *calculadora*, que posteriormente crearemos.

Métodos:
`int sumar(int a, int b);`
`int restar(int a, int b);`
`int multiplicar(int a, int b);`
`int division(int a, int b);`

### Creación de la clase calculadora.
Creamos la clase *calculadora* en el mismo paquete de la interfaz y una vez creada implementamos la interfaz en la clase `public class calculadora implements ICalculadora`. A continuación, usamos los métodos de la interfaz y programamos el funcionamento de los métodos.

Para comprobar que la calculadora es completamente funcional vamos a realizar test unitarios. Estos tests han sido realizados mediante JUnit comprobando que, efectivamente, la calculadora es totalmente válida.
