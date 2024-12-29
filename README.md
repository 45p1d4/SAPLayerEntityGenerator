# SAPLayerEntityGenerator

**SAPLayerEntityGenerator** es una herramienta para generar automáticamente archivos de entidades en TypeScript desde la metadata proporcionada por el Service Layer de SAP Business One.

## 🚀 Características

- **Conexión automática** al Service Layer de SAP Business One.
- **Extracción y parseo** de metadata desde el endpoint `/b1s/v1/$metadata`.
- **Generación automatizada** de archivos TypeScript que mapean entidades y propiedades.
- Opcionalmente, **incluye nombres de tablas** asociados a las entidades.

## 📚 Requisitos

- **Node.js** v14 o superior.
- Acceso a una instancia de SAP Business One con el Service Layer habilitado.
