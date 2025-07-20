# Enterprise-Java-Development-1.06

## Descripción

Este proyecto tiene como objetivo practicar conceptos de Programación Orientada a Objetos (POO) en Java, incluyendo **herencia**, **encapsulamiento** y **manejo de archivos**. El ejercicio consiste en implementar clases que representen empleados y pasantes, asegurando la correcta relación entre ellas y aplicando restricciones específicas.

---

## Requerimientos

- **Lenguaje:** Java (JDK 8 o superior recomendado)
- **IDE sugerido:** IntelliJ IDEA, Eclipse, VS Code o cualquier editor compatible con Java
- **Sistema operativo:** Windows, macOS o Linux
- **Git:** Tener instalado Git para clonar el repositorio y subir cambios

---

## Especificaciones

### Clases para empleados y pasantes

- Crear una clase `Employee` con las siguientes propiedades **privadas**:
  - `name` (String): nombre del empleado
  - `email` (String): correo electrónico del empleado
  - `age` (int): edad del empleado
  - `salary` (double): salario del empleado
- Implementar **getters** y **setters** para todas las propiedades.
- Crear una clase `Intern` que **hereda** de `Employee`.
  - En `Intern`, establecer un **límite de salario** de 20,000 (usar una constante).
  - Validar que no se cree ni actualice un objeto `Intern` con salario mayor al permitido.

### Manejo de datos y archivos

- Crear un programa principal que genere **10 objetos Employee** (pueden incluir algunos Intern).
- Imprimir **todas las propiedades** de cada empleado en un archivo llamado `employees.txt`.

### Buenas prácticas

- Usar modificadores de acceso adecuados (`private`, `protected`, `public`).
- Manejar casos extremos, como intentar crear o modificar un `Intern` con salario mayor al permitido (mostrar mensaje de error y evitar la acción).

---

## Pasos para ejecutar el proyecto

### 1. Clonar el repositorio

```sh
git clone https://github.com/FelixRodriguezG/Enterprise-Java-Development-1.06.git
cd Enterprise-Java-Development-1.06
```

### 2. Abrir el proyecto en tu IDE favorito

### 3. Compilar el proyecto

Ejecuta el comando de compilación de tu IDE o, si usas terminal:

```sh
javac *.java
```

### 4. Ejecutar el programa principal

Por ejemplo:

```sh
java Main
```

### 5. Verificar la salida

Se generará el archivo `employees.txt` con la información de los empleados en el directorio del proyecto.

---

## Envío

Cuando termines la tarea, sube tus cambios al repositorio y comparte la URL de tu repositorio como entrega.

---

## Consejos

- Aprovecha la **herencia** para evitar duplicación de código entre `Employee` e `Intern`.
- Usa **constantes** para valores fijos (como el límite salarial del pasante).
- Controla la **visibilidad** de los atributos y métodos para mantener la encapsulación.
- Maneja **errores** y casos extremos de manera clara y profesional.

---
