<div align="center">

# Sillage

### Tu colección. Tu contexto. Tu fragancia.

Una aplicación móvil open source que busca convertir la gestión de perfumes en una experiencia personal: organiza tu colección, registra cómo vives cada fragancia y descubre cuál encaja mejor con cada momento.

[![React Native](https://img.shields.io/badge/React_Native-0.88.1-20232A?logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-58-000020?logo=expo&logoColor=white)](https://expo.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-6-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

[**Explorar el proyecto**](#-sobre-sillage) · [**Roadmap**](#-roadmap) · [**Instalación**](#-quick-start) · [**Contribuir**](#-contribuir)

</div>

---

## 🌿 Sobre Sillage

Sillage es un proyecto open source en desarrollo que aspira a ser un asistente personal de perfumería. No quiere ser solamente otro catálogo: busca conectar la información de cada fragancia con el contexto y las experiencias de quien la utiliza.

La aplicación tendrá en cuenta factores como el clima, la temperatura, la ocasión, las preferencias olfativas y el historial personal para ofrecer recomendaciones cada vez más relevantes.

> **La idea central:** cuanto más uses Sillage, mejor podrá comprender tus gustos y ayudarte a aprovechar tu colección.

## ✨ Características principales

- **Fragrance Wardrobe:** registra, organiza y consulta tu colección personal de perfumes.
- **Scent Scan:** facilita la incorporación de fragancias mediante código de barras, reconocimiento de etiquetas y búsqueda manual.
- **Smart Scent Advisor:** recomienda perfumes considerando clima, temperatura, humedad, ocasión y preferencias.
- **Scent of the Day:** propone una fragancia para el día y explica por qué puede encajar con el contexto.
- **Fragrance Journal:** guarda experiencias de uso, duración percibida, proyección y valoraciones.
- **Perfil olfativo:** aprende progresivamente de tus gustos, elecciones y comentarios.
- **Colección y estadísticas:** ayuda a descubrir hábitos de uso y perfumes que llevan tiempo sin salir del estante.

Estas son las funcionalidades previstas para el producto. Su disponibilidad real dependerá del avance indicado en el roadmap.

## 🧭 Roadmap

El desarrollo se realizará por etapas. Las casillas marcadas representan trabajo ya presente en el repositorio; las demás son objetivos pendientes, no funcionalidades que deban darse por terminadas.

### MVP — Experiencia esencial

- [ ] Registro e inicio de sesión.
- [ ] Catálogo inicial de fragancias.
- [ ] Colección personal (Fragrance Wardrobe).
- [ ] Búsqueda manual y registro de perfumes.
- [ ] Consulta de información meteorológica.
- [ ] Primer motor de recomendaciones basado en reglas.
- [ ] Scent of the Day.
- [ ] Diario de experiencias básico.
- [ ] Perfil olfativo inicial.

### Evolución del producto

- [ ] Escaneo de códigos EAN/UPC.
- [ ] Catálogo colaborativo con aportes de usuarios y validación de datos.
- [ ] Reconocimiento de etiquetas mediante OCR.
- [ ] Personalización progresiva del algoritmo.
- [ ] Estadísticas de uso y colección.
- [ ] Notificaciones configurables.
- [ ] Evaluación e implementación de gamificación.

### Exploración futura

- [ ] Vitrina virtual de colección.
- [ ] Evaluación de visualización 3D con React Three Fiber.
- [ ] Posible experiencia de realidad aumentada.

El roadmap puede cambiar según las pruebas, las contribuciones de la comunidad y las prioridades del proyecto.

## 🧰 Stack tecnológico

| Área | Tecnología |
| --- | --- |
| Aplicación móvil | React Native |
| Framework y herramientas | Expo |
| Lenguaje | TypeScript |
| Navegación | Expo Router |
| Motor de desarrollo | Node.js + npm |

La arquitectura de backend, persistencia y servicios externos se definirá e incorporará conforme avance el MVP. Las tecnologías futuras no se consideran dependencias funcionales de la aplicación actual.

## 🚀 Quick Start

### Requisitos

- Node.js en una versión compatible con tu versión de Expo.
- npm (el repositorio incluye `package-lock.json`).
- Git.
- Expo Go o un emulador/simulador para ejecutar la aplicación.

### 1. Clonar el repositorio e instalar dependencias

```bash
git clone https://github.com/KraunDew/sillage-mobile.git
cd sillage-mobile
npm install
```

### 2. Configurar variables de entorno

Actualmente, el repositorio incluye un archivo `.env.example` con los nombres de las variables necesarias. Podrás crear tu archivo local:

```bash
cp .env.example .env
```

Completa los valores localmente y **no subas secretos ni archivos `.env` al repositorio**. Las variables `EXPO_PUBLIC_*` se incorporan al bundle de la aplicación y no deben contener claves privadas ni credenciales sensibles.

### 3. Iniciar Expo

```bash
npx expo start
```

Después, abre la aplicación con Expo Go, un emulador de Android o un simulador de iOS. También puedes usar:

```bash
npm run android
npm run ios
npm run web
```

## 🗂️ Estructura del proyecto

```text
sillage-mobile/
├── assets/          # Recursos estáticos
├── scripts/         # Scripts del proyecto
├── src/             # Código fuente de la aplicación
├── app.json         # Configuración de Expo
├── package.json     # Dependencias y scripts
├── package-lock.json
├── tsconfig.json
└── LICENSE
```

La estructura puede evolucionar a medida que se incorporen los módulos del producto.

## 🤝 Contribuir

Sillage es un proyecto abierto a ideas, mejoras y contribuciones.

Puedes ayudar de distintas formas:

- Reportando errores o proponiendo mejoras mediante **Issues**.
- Sugiriendo funcionalidades y compartiendo casos de uso.
- Mejorando la documentación.
- Enviando Pull Requests pequeños y enfocados.

Antes de implementar cambios grandes, abre un Issue para conversar sobre el enfoque y evitar trabajo duplicado.

## 📄 Licencia

Este proyecto está distribuido bajo la licencia **GNU General Public License v3.0 (GPL-3.0)**. Consulta el archivo [`LICENSE`](LICENSE) para conocer sus términos.

---

<div align="center">

Hecho con ☕ y curiosidad por el mundo de las fragancias.

**Sillage** · Open source, en construcción.

</div>
