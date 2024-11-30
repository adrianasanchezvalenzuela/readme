# Proyecto Cliente-Servidor
## **Integrantes**
- Adriana Sánchez Valenzuela, 223220776
- Samara Acosta Ibarra, 223203127
- Hilary del Carmen Rangel Zambrano, 223210499

## **Puntaje por el que vamos**
- 100% + 10 puntos extras

## **Uso de IA Generativa**
- Herramientas usadas:
  - ChatGPT para ayuda en la lógica del programa.

## **Instrucciones de Ejecución**
### **Argumentos necesarios:**
- **Cliente:** `localhost 4242 libros akira 12`
- **Servidor:** `4242 akira 12`

### **Pasos para ejecución:**
1. Inicia el `Servidor` con los argumentos indicados.
2. Establece la conexión desde el `Cliente`.
3. Ejecuta los siguientes comandos desde el Cliente:
    - `cifrar:`
    - `mandar:libros_cifrados`
4. En el Servidor:
    - `descifrar:libros_cifrados`
    - `mandar:libros_descifrados`
5. En el Cliente:
    - `compara:libros_descifrados`

## **Dependencias del proyecto**
1. Java JDK 17+.
2. Biblioteca Apache Commons Codec (para hashing).
3. Librería JSON Simple (para manejo de archivos JSON).
4. NetBeans o cualquier IDE compatible con proyectos Java.
