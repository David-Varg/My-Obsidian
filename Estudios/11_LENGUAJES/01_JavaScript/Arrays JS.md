### **TypedArrays**
Esto es para *Javascript*, son llamados TypedArrays y a diferencia de un Array normal en donde se puede almacenar un texto con un número y un float en el mismo Array, estos están diseñados para manejar exclusivamente datos numéricos binarios de forma muy eficiente.

1. *Int32Array (Enteros de 32 bits)*
Este tipo de array se utiliza para almacenar *numeros enteros con signo*. Si no sabes que es mira: [[07. Representación de Enteros]].
- **Capacidad**: Cada elemento ocupa 4 bytes (32 bits).
- **Rango**: Puede almacenar valores desde $-2,147,483,648$ hasta $-2,147,483,647$.
- **Uso**: Es ideal cuando necesitas trabajar con conteos, índices o datos que sabes que nunca tendrán decimales. Al estar limitado a 32 bits, el procesamiento es extremadamente rápido para la CPU.

2. *Float64Array (Decimales de 64 bits)*
Este es el número estandar que usa JavaScript para casi todos sus números por defecto (basado en el estándar [[08. IEEE 754|IEEE 754]]).
- **Capacidad**: Cada elemento ocupa 8 bytes.
- **Rango**: Permite almacenar números con una precisión decimal muy alta y valores mucho más grandes o pequeños que el anterior.
- **Uso**: Cálculos científicos, coordenadas geográficas precisas o cualquier situación donde los decimales sean fundamentales.
