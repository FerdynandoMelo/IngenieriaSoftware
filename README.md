# 🏨 Sistema de Gestión de Reservas - Hotel Pacific Reef
**Evaluación Final Transversal (EFT) - Ingeniería de Software (PRY3211)**

Este proyecto consiste en una solución integral para la gestión de reservas hoteleras, permitiendo a los clientes buscar habitaciones y realizar reservas, mientras que el administrador puede gestionar el inventario y visualizar el estado del hotel en tiempo real.

## 🚀 Repositorio y Documentación
* **Repositorio GitHub:** [https://github.com/FerdynandoMelo/IngenieriaSoftware](https://github.com/FerdynandoMelo/IngenieriaSoftware)
* **Gestión del Proyecto:** [Tablero Trello - Metodología Scrum](https://trello.com/b/tu-link-de-trello)
* **Ambiente de Base de Datos:** Oracle Cloud Autonomous DB.

## 🛠️ Tecnologías Utilizadas
* **Front-end:** [Framework seleccionado, ej: React/Angular/HTML5]
* **Back-end:** [Node.js / Python / Java]
* **Base de Datos:** Oracle SQL (Modelo Relacional)
* **Modelamiento:** UML 4+1 (Diagramas de Clases, Casos de Uso y Actividad)
* **Diseño UI/UX:** Figma

## 📋 Arquitectura del Sistema (UML 4+1)
El sistema se basa en 4 vistas principales para asegurar la escalabilidad:
1.  **Vista Escenario:** Casos de uso para Turista y Administrador.
2.  **Vista Lógica:** Modelo de clases `Hotel`, `Habitacion`, `Cliente` y `Reserva`.
3.  **Vista de Proceso:** Flujo de reserva desde búsqueda hasta comprobante.
4.  **Modelo de Datos:** Implementación relacional en Oracle con integridad referencial.

## ⚙️ Instalación y Configuración
1.  Clonar el repositorio:
    ```bash
    git clone [https://github.com/FerdynandoMelo/IngenieriaSoftware.git](https://github.com/FerdynandoMelo/IngenieriaSoftware.git)
    ```
2.  Importar el esquema de base de datos ubicado en `/database/schema.sql` en tu instancia de Oracle.
3.  Configurar las variables de entorno en el archivo `.env` (si aplica).
4.  Ejecutar el servidor de desarrollo.

## ✅ Definition of Done (DoD)
Para este proyecto, se consideró un ítem como "Hecho" cuando:
- [x] El código está documentado y versionado en GitHub.
- [x] Las pruebas funcionales en el Manual de Testing fueron aprobadas.
- [x] La interfaz es coherente con los prototipos de Figma.
- [x] Existe integración completa entre el Front-end y la Base de Datos.

## 👤 Desarrollador
* **Ferdynando Melo** - Analista Programador Computacional - Duoc UC.
