# Crud Farmacia 🧾🏥

## Descripción general
Prys es una aplicación de escritorio desarrollada en Java (proyecto NetBeans / Ant) para la gestión básica de una farmacia o punto de venta farmacéutico. Incluye módulos para manejar clientes, empleados y medicamentos, y un menú principal para navegar entre funcionalidades.

## ¿Para quién?
- Pequeñas farmacias o tiendas que necesitan una gestión local básica.
- Estudiantes y desarrolladores que desean ver un ejemplo de proyecto Java de escritorio con estructura NetBeans/Ant.
- Proyectos académicos o prototipos rápidos.

## Funcionalidades principales
- Gestión de clientes: registro, edición y consulta.
- Gestión de empleados: administración del personal.
- Gestión de medicamentos: catálogo y atributos básicos de productos.
- Menú principal: acceso centralizado a los módulos del sistema.

## Tecnologías
- Lenguaje: Java
- Build: Ant (build.xml)
- IDE / proyecto: NetBeans (nbproject)

## Estructura del proyecto (relevante)
```
PryFinal-CZJ/PryFinal/
  build.xml
  manifest.mf
  nbproject/
  src/
    Farmacia/
      Cliente.java
      Empleado.java
      MainMenu.java
      Medicamentos.java
    Imeco/
```

## Requisitos
- JDK (recomendado JDK 8+)
- Apache Ant (si se quiere usar la compilación por consola)
- NetBeans (opcional, para abrir y ejecutar el proyecto desde el IDE)

## Cómo ejecutar
1. Clona el repositorio:
```bash
git clone https://github.com/Jeancgonzalez/Prys.git
```
2. Abrir en NetBeans:
   - Importar/abrir `PryFinal-CZJ/PryFinal` como proyecto NetBeans y Ejecutar desde el IDE.

O con Ant (línea de comandos):
```bash
cd PryFinal-CZJ/PryFinal
ant clean
ant
```

## Diseño y mantenimiento
- Código modular en paquetes (por ejemplo `src/Farmacia`) para separar responsabilidades.
- Fácil de extender añadiendo nuevos módulos (informes, facturación, control de stock avanzado).

## Autores
- Jeancgonzalez

## Enlace
- https://github.com/Jeancgonzalez/Prys
