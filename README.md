# 🌱 EcoScan – Reciclaje Inteligente con Kotlin + Jetpack Compose

![EcoScan Banner](https://img.shields.io/badge/Kotlin-Jetpack%20Compose-blueviolet?style=for-the-badge&logo=kotlin)  
![Status](https://img.shields.io/badge/Estado-MVP%20en%20desarrollo-brightgreen?style=for-the-badge)  
![License](https://img.shields.io/badge/Licencia-MIT-yellow?style=for-the-badge)

---

## 📖 Descripción

**EcoScan** es un proyecto **MVP (Producto Mínimo Viable)** de una aplicación Android desarrollada en **Kotlin con Jetpack Compose**.  
La app permite a los usuarios **escanear objetos con la cámara o la galería** para clasificarlos como reciclables (plástico, papel, vidrio, metal u orgánico), guardarlos en un historial y visualizar estadísticas de su progreso en la reutilización de materiales.

Este proyecto nace como idea de **startup innovadora en sostenibilidad**, con el objetivo de **gamificar el reciclaje** y motivar a más personas a cuidar el medio ambiente.

---

## 🚀 Características principales

- 📱 **UI moderna con Jetpack Compose**: navegación entre pantallas fluida y adaptable.
- 🧭 **Navegación declarativa**: Inicio → Escanear → Historial → Perfil.
- 🗂️ **DataClass y JSON**: manejo estructurado de datos locales y mock de API.
- 📊 **Historial de objetos reciclados**: registro visual con estadísticas.
- 📷 **Acceso a hardware**:  
  - Cámara para tomar fotos de objetos.  
  - Galería para seleccionar imágenes existentes.  
- 🔒 **Permisos dinámicos**: manejo seguro de cámara y almacenamiento.
- 📡 **ViewModel + StateFlow**: arquitectura limpia y desacoplada.
- ♻️ **Gamificación básica**: puntos y chips de progreso por material reciclado.

---

## 🛠️ Tecnologías utilizadas

- **Lenguaje:** Kotlin  
- **Framework UI:** Jetpack Compose (Material 3)  
- **Arquitectura:** MVVM (Model - ViewModel - View)  
- **Gestión de estado:** ViewModel + StateFlow  
- **JSON:** datos mock para tipos de reciclaje  
- **Hardware:** Cámara y Galería (independientes del resto del proyecto)  
- **Permisos:** ActivityResultContracts + Accompanist Permissions  

---

## 🖼️ Mockup de la primera pantalla (Inicio)

```json
{
  "Pantalla": "Inicio",
  "Botones": [
    {"nombre": "Escanear", "estilo": "Botón circular con gradiente verde", "acción": "Abrir cámara o galería"},
    {"nombre": "Ver Historial", "estilo": "Botón rectangular con borde suave", "acción": "Ir al historial"}
  ],
  "Colores": {
    "Primario": "#2E7D32",
    "Secundario": "#81C784",
    "Fondo": "#F6FFF7",
    "Texto": "#0B3D20"
  }
}
