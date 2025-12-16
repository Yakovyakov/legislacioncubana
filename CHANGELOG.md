# Historial de Cambios

Registro de todas las versiones publicadas de Legislación Cubana.

## [1.1.0] - 2025-12-12

### 🚀 Nuevas Características

- **Seguridad OTA**: Sistema de verificación de firmas digitales ECDSA para `latest.json`, reemplazando SSL Pinning.
- **Modo oscuro**: Soporte completo con selector manual (claro/oscuro/sistema).
- **Mensajes de Compartición**: Contactos oficiales de AFBRITTO añadidos al compartir documentos sin enlace público.

### 🐛 Correcciones

- **Almacenamiento**: Migración del directorio de descargas al caché de la app, resolviendo errores `ENOENT` en Android 11+.
- **Interfaz**: Corrección de solapamiento del teclado virtual con campos de formulario.
- **Rendimiento**: Optimización del componente `DocumentCard` eliminando renders innecesarios.

### 🔧 Cambios Técnicos

- **Arquitectura**: Nuevo módulo nativo Kotlin (`UpdateVerifierModule`) para verificación ECDSA.
- **Red**: Configuración actualizada para permitir HTTP en desarrollo.

### 📋 Notas de Actualización

- **Desarrolladores**: Configurar servidor para firmar `latest.json` con clave privada ECDSA.
- **Usuarios**: Actualización necesaria para recibir actualizaciones seguras. Mejoras en fluidez y compartición.

## [1.0.1] - Noviembre 2025

### 🛠️ Correcciones y Mejoras

#### ✨ Nuevo

- **APK universal** que funciona en todos los dispositivos
- **Nuevo icono** de aplicación

#### 🔧 Ajustes

- **Enlace de Telegram** actualizado en sección de contacto
- **Enlace a sitio web** actualizado en sección de contacto
- **Eliminadas siglas** de emisoras en visualización de documentos
- **Mejoras de rendimiento** en dispositivos de gama baja

#### 📱 Compatibilidad Expandida

- **universal**: Todas las arquitecturas

----

## [1.0.0] - 2025-11-19

### 🎉 Lanzamiento Inicial

#### ✨ Nuevas Funcionalidades

- **Sistema completo de búsqueda** con múltiples filtros
- **Visualización de documentos** en tarjetas optimizadas
- **Acceso a PDFs** oficiales de la Gaceta
- **Sistema de actualizaciones** automático
- **Compartir documentos** con información completa

#### 🔍 Búsqueda y Filtros

- Filtro por **emisor** (61 organismos disponibles)
- Filtro por **tipo de documento** (24 tipos)
- Filtro por **tipo de gaceta** (Ordinaria, Extraordinaria, Especial)
- Búsqueda por **número de documento**
- Búsqueda por **año** de emisión
- Búsqueda de **texto** en contenido

#### 📄 Gestión de Documentos

- Tarjetas informativas con diseño responsive
- Expansión de texto largo ("Ver más/Ver menos")
- Acciones rápidas: Copiar, PDF, Compartir
- Paginación infinita en resultados

#### ⚡ Experiencia de Usuario

- Interfaz intuitiva y fácil de navegar
- Indicadores de carga y estados
- Manejo robusto de errores
- Navegación con botón back físico

#### 🔄 Actualizaciones

- Verificación automática de nuevas versiones
- Descarga e instalación seamless
- Notificaciones de actualizaciones
- Fallback para descarga manual

#### 📱 Compatibilidad

- **Android 5.0+** (API 21 y superior)
- Optimizada para móviles y tablets
- Múltiples densidades de pantalla

----

## Información Técnica

### Versionado

Seguimos [Versionado Semántico](https://semver.org/):

- **MAYOR**: Cambios incompatibles
- **MENOR**: Nuevas funcionalidades
- **PARCHES**: Correcciones de bugs

### Soporte

- **Versión actual**: 1.1.0
- **Versión mínima de Android**: 5.0 (API 21)
- **Arquitecturas soportadas**: arm64-v8a

### Verificación

Cada release incluye:

- ✅ Checksum SHA256 para verificación
- ✅ Changelog detallado
- ✅ Compatibilidad verificada

----

**Última actualización:** 12 de Diciembre, 2025

**Soporte técnico:** <yyak0423@gmail.com>
