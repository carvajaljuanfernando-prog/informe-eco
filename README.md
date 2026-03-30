# Informe Ecocardiográfico — Dr. Juan Fernando Carvajal

Sistema de informe ecocardiográfico clínico desarrollado para uso en consulta privada y en el Instituto del Corazón de Bucaramanga.

## 🔗 Acceso directo

**[→ Abrir aplicación](https://carvajaljuanfernando-prog.github.io/informe-eco/)**

## ✨ Características

- **16 secciones clínicas** con cálculos automáticos en tiempo real
- **Clasificaciones ASE/EACVI 2016** para función diastólica, strain y probabilidad de HP (ESC/ERS 2022)
- **Preformatos inteligentes** que se autocompletan con los valores ya ingresados
- **Trastornos segmentarios** con sistema de múltiples filas combinables
- **Dictado por voz** (Chrome/Edge) — campo individual o modo secuencial
- **Exportación PDF** con diseño compacto de 2 columnas (tabla numérica + texto descriptivo)
- **Funciona 100% sin internet** — archivo HTML autosuficiente sin dependencias externas
- **Compatible con iPad** — interfaz responsiva adaptada para uso táctil

## 📋 Secciones incluidas

| # | Sección | Cálculos automáticos |
|---|---------|---------------------|
| 01 | Datos del Paciente | SC (Du Bois), IMC |
| 02 | Calidad Técnica y Ritmo | — |
| 03 | Ventrículo Izquierdo | Masa VI, IRP, patrón geométrico, FA |
| 04 | Función Diastólica | E/A, E/e', grado ASE 2016 |
| 05 | Aurícula Izquierda | Volumen indexado, clasificación |
| 06 | Ventrículo Derecho | Función + 3 diámetros (basal/medio/longitudinal) |
| 07 | Aurícula Derecha | Clasificación por área (ASE 2015), FOP/CIA |
| 08 | Válvula Mitral | Área PHT, clasificación Carpentier |
| 09 | Válvula Aórtica | AVA (ecuación de continuidad), clasificación EA/IA |
| 10 | Válvula Tricúspide | PSAP (4v² + PAD) |
| 11 | Válvula Pulmonar | — |
| 12 | Aorta y Grandes Vasos | — |
| 13 | Arteria Pulmonar y VCI | PAD estimada, AP/Ao ratio |
| 14 | Pericardio | — |
| 15 | Hallazgos Adicionales | — |
| 16 | Strain Ventricular | GLS VI, RVLS (clasificación ASE/EACVI) |
| 17 | Probabilidad HP | Algoritmo ESC/ERS 2022, TAPSE/PSAP |

## 🖨️ Formato PDF

El informe exportado incluye:
- **Encabezado** con logo, nombre del médico, datos del paciente e identificación
- **Columna izquierda**: tabla compacta con todos los valores numéricos
- **Columna derecha**: textos descriptivos por sección
- **Conclusiones** en recuadro destacado

## 🎙️ Dictado por voz

Requiere **Google Chrome** o **Microsoft Edge** y conexión HTTPS (funciona automáticamente desde GitHub Pages).

- Botón 🎙 individual en cada campo numérico
- Botón flotante 🎙 para modo secuencial (recorre todos los campos vacíos)
- Comandos: decir el número; "saltar" o "siguiente" para omitir; "parar" para detener

## 📱 Uso en iPad

1. Abrir la URL de GitHub Pages en Safari
2. Tocar ⬆ Compartir → **"Agregar a pantalla de inicio"**
3. Se instala como app con ícono propio

## 🛠️ Tecnología

- HTML5 + CSS3 + JavaScript vanilla (sin frameworks)
- Web Speech API para reconocimiento de voz
- Archivo único autosuficiente (~744 KB con logo embebido)

## 👨‍⚕️ Autor

**Dr. Juan Fernando Carvajal Estupiñán**  
Cardiólogo — Bucaramanga, Colombia  
Centro Médico Carlos Ardila Lulle · Instituto del Corazón de Bucaramanga  
Semillero de Investigación CardioUDES — UDES

---
*Desarrollado con fines clínicos y académicos. No reemplaza el juicio clínico del especialista.*
