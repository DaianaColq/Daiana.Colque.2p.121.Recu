# Daiana.Colque.2p.121.Recuperatorio
Descripción
Este proyecto implementa un sistema en Java para gestionar torneos de videojuegos organizados por una empresa de eSports. Permite almacenar, filtrar, ordenar y guardar la información de los torneos en archivos binarios y archivos CSV compatibles con Excel.

Estructura del proyecto
css
Copiar
Editar
TorneosVideojuegos/
│
├── src/
│   ├── modelo/
│   │   ├── Torneo.java
│   │   ├── TorneoVideojuego.java
│   │   ├── CategoriaVideojuego.java
│   │   ├── CSVSerializable.java
│   │   ├── Gestionable.java
│   │   ├── GestorEventos.java
│   │   └── AppConfig.java
│   └── tester/
│       └── Main.java (Tester)
│
├── data/
│   ├── torneos.ser      (Archivo binario generado)
│   └── torneos.csv      (Archivo CSV generado)
│
└── README.md
Requisitos previos
Java JDK 8 o superior

IDE recomendado: NetBeans (se usó para desarrollo y prueba)

Carpeta data creada en la raíz del proyecto para almacenamiento de archivos

Cómo ejecutar
Abrir el proyecto en NetBeans o en el IDE que uses.

Compilar todo el proyecto.

Ejecutar la clase tester.Main (no modificar).

El programa realizará:

Agregar torneos de videojuegos.

Mostrar torneos en consola.

Filtrar y ordenar torneos.

Guardar y cargar torneos desde archivos binarios (.ser) y CSV (.csv).

Mostrar los resultados por consola.

Archivos generados
data/torneos.ser : Archivo binario que guarda la lista de torneos serializados.

data/torneos.csv : Archivo de texto con formato CSV separado por punto y coma (;), compatible con Excel.
