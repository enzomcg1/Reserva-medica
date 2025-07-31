
# Comparativa de Frameworks JavaScript: React vs Angular

## 📌 React

### ¿Qué es y para qué se utiliza?
React es una biblioteca JavaScript de código abierto para construir interfaces de usuario, especialmente en aplicaciones web de una sola página (SPA). Se basa en una arquitectura de componentes reutilizables y estados que permiten una renderización eficiente del DOM.

### ¿Quién lo desarrolla o mantiene?
Fue desarrollado por **Facebook (ahora Meta)** y actualmente se mantiene como proyecto de código abierto con una gran comunidad activa.

### ¿Cuál es su filosofía o enfoque principal?
React adopta una filosofía **declarativa y basada en componentes**, donde cada parte de la interfaz se define como un componente independiente que puede reutilizarse y gestionarse fácilmente. Utiliza un **DOM virtual** para mejorar el rendimiento en actualizaciones de la UI.

### ✅ Ventajas principales
- Gran comunidad y ecosistema maduro.
- Alto rendimiento gracias al Virtual DOM.
- Componentes reutilizables y encapsulados.
- Fácil integración con otras bibliotecas.
- React Native permite reutilizar código para apps móviles.

### ❌ Desventajas o limitaciones
- Solo cubre la vista, se necesita agregar herramientas para routing, manejo de estado, etc.
- La curva de aprendizaje puede crecer al combinar con muchas herramientas externas.
- JSX (mezcla de HTML con JS) puede ser difícil de entender inicialmente.

### 📌 Proyectos conocidos que lo utilizan
- Facebook
- Instagram
- WhatsApp Web
- Netflix
- Airbnb

### 🔧 Fragmento de código – Hello World (React)
```jsx
import React from 'react';
import ReactDOM from 'react-dom/client';

function App() {
  return <h1>Hola Mundo desde React</h1>;
}

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<App />);
```

---

## 📌 Angular

### ¿Qué es y para qué se utiliza?
Angular es un framework completo para el desarrollo de aplicaciones web modernas. Permite construir SPAs usando TypeScript, HTML y CSS, y proporciona todas las herramientas necesarias integradas: enrutamiento, formularios, servicios HTTP, etc.

### ¿Quién lo desarrolla o mantiene?
Es desarrollado y mantenido por **Google** y su comunidad de código abierto.

### ¿Cuál es su filosofía o enfoque principal?
Angular adopta un enfoque **todo-en-uno (full framework)**, basado en el patrón **MVC (Modelo-Vista-Controlador)** y fuertemente estructurado con TypeScript. Promueve buenas prácticas desde el inicio y una arquitectura escalable.

### ✅ Ventajas principales
- Framework completo: ya incluye routing, formularios, peticiones HTTP, etc.
- Escrito en TypeScript, lo que aporta tipado fuerte y herramientas de desarrollo avanzadas.
- Muy escalable para aplicaciones grandes.
- Soporte oficial a largo plazo por parte de Google.
- Buen rendimiento con compilación Ahead-Of-Time (AOT).

### ❌ Desventajas o limitaciones
- Curva de aprendizaje más alta (arquitectura compleja, múltiples conceptos).
- Verboso: requiere más configuración y boilerplate.
- Menor flexibilidad que React al momento de elegir herramientas.

### 📌 Proyectos conocidos que lo utilizan
- Gmail
- Google Cloud Console
- Forbes
- Microsoft Office Online
- Santander Río (banco)

### 🔧 Fragmento de código – Hello World (Angular)
```ts
// app.component.ts
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  template: `<h1>Hola Mundo desde Angular</h1>`,
})
export class AppComponent { }
```

---

## 📊 Comparativa Final

| Característica         | React                           | Angular                          |
|------------------------|----------------------------------|----------------------------------|
| Tipo                   | Biblioteca (UI)                 | Framework completo               |
| Lenguaje base          | JavaScript + JSX                | TypeScript                       |
| Curva de aprendizaje   | Media                           | Alta                             |
| Tamaño del bundle      | Menor                           | Mayor                            |
| Rendimiento            | Alto (con Virtual DOM)          | Muy bueno (AOT + Ivy)            |
| Comunidad              | Muy grande y activa             | Grande y con soporte de Google   |
| Estructura             | Flexible, menos estructurado    | Muy estructurado y opinativo     |
| Uso en empresas        | Facebook, Netflix, Airbnb       | Google, Microsoft, Forbes        |
| Escalabilidad          | Alta con herramientas externas  | Alta nativamente                 |

---

## 🤔 ¿Cuál me gustaría aprender o profundizar más?

Me gustaría **profundizar más en React**, ya que su flexibilidad me permite iniciar proyectos pequeños e ir integrando herramientas según lo necesite. Además, su enorme comunidad y la posibilidad de trabajar tanto en web como en aplicaciones móviles (React Native) lo convierten en una excelente opción para proyectos modernos y versátiles.
