# Sistema de Gestión de Usuarios (Empleados)

Sistema de gestión de empleados desarrollado en Java que permite administrar información de empleados mediante una interfaz gráfica interactiva.

## 📋 Descripción

Este sistema permite gestionar información de empleados de una empresa, incluyendo sus datos personales y salariales. El programa ofrece un menú interactivo mediante ventanas de diálogo (JOptionPane) para realizar diversas operaciones sobre los empleados registrados.

## ✨ Características

- **Agregar empleados**: Registro de nuevos empleados con sus datos completos
- **Mostrar empleados**: Visualización de todos los empleados registrados
- **Búsqueda por nombre**: Localización de empleados específicos
- **Cálculo de salario promedio**: Estadística del salario promedio de todos los empleados
- **Empleado con salario más alto**: Identificación del empleado mejor pagado
- **Empleado con salario más bajo**: Identificación del empleado con menor salario

## 🏗️ Estructura del Proyecto

```
SISTEMA-DE-GESTION-DE-USUARIOS/
├── EMPLEADOS/
│   ├── src/
│   │   ├── ECP02.java              # Clase principal con menú interactivo
│   │   ├── Empleado.java           # Clase que representa un empleado
│   │   └── GestionUsuarios.java    # Clase para gestionar la colección de empleados
│   ├── build/
│   └── nbproject/
```

## 📦 Clases Principales

### `Empleado`
Clase que representa un empleado con los siguientes atributos:
- **nombre**: Nombre del empleado
- **edad**: Edad del empleado
- **departamento**: Departamento al que pertenece
- **salario**: Salario del empleado

### `GestionUsuarios`
Clase que gestiona una colección de empleados (máximo 5 empleados) con métodos para:
- Agregar empleados
- Mostrar todos los empleados
- Buscar empleados por nombre
- Calcular estadísticas salariales

### `ECP02`
Clase principal que contiene el método `main` y el menú interactivo del sistema.

## 🚀 Requisitos

- **Java JDK** 8 o superior
- **IDE** (NetBeans recomendado, aunque puede usarse cualquier IDE o compilador de línea de comandos)

## 💻 Compilación y Ejecución

### Usando NetBeans

1. Abre el proyecto en NetBeans
2. Haz clic derecho en el proyecto y selecciona **Clean and Build**
3. Ejecuta el proyecto con **Run** o presiona `F6`
4. La clase principal es `ECP02`

### Usando línea de comandos

```bash
# Compilar
cd EMPLEADOS/src
javac *.java

# Ejecutar
java ECP02
```

## 📖 Uso del Sistema

Al ejecutar el programa, se mostrará un menú con las siguientes opciones:

1. **Agregar un nuevo empleado**: Permite ingresar los datos de un nuevo empleado
2. **Mostrar la información de todos los empleados**: Lista todos los empleados registrados
3. **Buscar un empleado por nombre**: Busca un empleado específico por su nombre
4. **Calcular el salario promedio de todos los empleados**: Muestra el promedio salarial
5. **Buscar el empleado con el salario más alto**: Identifica al empleado mejor pagado
6. **Buscar el empleado con el salario más bajo**: Identifica al empleado con menor salario
7. **Salir**: Cierra la aplicación

## ⚠️ Limitaciones

- El sistema tiene una capacidad máxima de **5 empleados**
- Los datos no se persisten entre ejecuciones (se pierden al cerrar el programa)
- La interfaz utiliza ventanas de diálogo (JOptionPane)

## 👤 Autor

**Fabia**

## 📝 Notas

- Este proyecto fue desarrollado como parte de un ejercicio académico
- El sistema utiliza arrays estáticos para almacenar los empleados
- La búsqueda por nombre es case-insensitive (no distingue entre mayúsculas y minúsculas)

