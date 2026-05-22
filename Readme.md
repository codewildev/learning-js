---
id: 1766436969-FRONT-PAGE
aliases:
  - javascript
tags:
  - leanirng
  - javascript
  - roadmap
---

# JavaScript - Roadmap de Aprendizaje

## Introducción

JavaScript es un lenguaje de programación ligero, interpretado y orientado a objetos con [funciones de primera clase](https://en.wikipedia.org/wiki/First-class_function).

Es un lenguaje de scripts dinámico, multiparadigma y de un solo hilo (single-threaded), [basado en prototipos](https://es.wikipedia.org/wiki/Programaci%C3%B3n_basada_en_prototipos). Admite estilos de programación orientados a objetos, imperativa y funcional.

Originalmente, JavaScript se ejecutaba del lado del cliente en la web para programar el comportamiento de las páginas ante eventos. No obstante, hoy en día su ecosistema permite el desarrollo tanto en el frontend como en el backend.

## Sobre este Roadmap

Este roadmap se ha elaborado con base en la documentación de **MDN Web Docs** y **roadmap.sh**. He diseñado una ruta de aprendizaje que va desde lo más básico hasta lo avanzado. El objetivo es equilibrar la teoría y la práctica para dominar el lenguaje que sigue revolucionando el desarrollo web.

---

## 📚 Índice del Roadmap

- [Nivel 1: Fundamentos Esenciales](#nivel-1-fundamentos-esenciales)
- [Nivel 2: Conceptos Intermedios](#nivel-2-conceptos-intermedios)
- [Nivel 3: Conceptos Avanzados](#nivel-3-conceptos-avanzados)
- [Nivel 4: JavaScript Moderno](#nivel-4-javascript-moderno)
- [Nivel 5: Especialización](#nivel-5-especialización)

---

# Nivel 1 — Fundamentos Esenciales de JavaScript

## 1.1 Introducción a JavaScript

- [ ]  [¿Qué es JavaScript?](./level_1/introduction/1779399251-WYVD.md)
    - Historia de JavaScript
    - ECMAScript
    - Versiones ES5, ES6+
    - Motores de JavaScript (V8, SpiderMonkey)
    - JavaScript vs Java
    - Single Thread y Non-blocking
- [ ]  [¿Dónde se ejecuta JavaScript?](./level_1/introduction/1779401184-ZIMV.md)
    - Navegador
    - Node.js
    - Runtime environments
- [ ]  [Cómo ejecutar JavaScript](./level_1/introduction/1779401347-OHOW.md)
    - DevTools
    - Console
    - Node.js
    - CodePen / JSFiddle

---

## [1.2 Variables y Scope](./level_1/variable_scopes/1779399393-BDGE.md)

- [ ]  Declaración de variables
    - `var`
    - `let`
    - `const`
- [ ]  Scope
    - Global scope
    - Function scope
    - Block scope
    - Lexical scope
- [ ]  Hoisting
    - Hoisting en funciones
    - Hoisting en variables
- [ ]  Temporal Dead Zone (TDZ)
- [ ]  Reglas de nomenclatura

---

## [1.3 Tipos de Datos](./level_1/data_type/1779399831-FNQS.md)

### Tipos Primitivos

- [ ]  `string`
- [ ]  `number`
- [ ]  `bigint`
- [ ]  `boolean`
- [ ]  `undefined`
- [ ]  `null`
- [ ]  `symbol`

### Tipos Complejos

- [ ]  `Object`
- [ ]  Arrays
- [ ]  Functions

### Conversión de Tipos

- [ ]  Type coercion
- [ ]  Conversión explícita
- [ ]  Truthy y Falsy

### Operadores de Tipos

- [ ]  `typeof`
- [ ]  `instanceof`

---

## [1.4 Operadores](./level_1/operators/1779400068-GYRF.md)

### Operadores Aritméticos

- [ ]  `+`
- [ ]  `-`
- [ ]  `*`
- [ ]  `/`
- [ ]  `%`
- [ ]  `**`

### Operadores de Comparación

- [ ]  `==`
- [ ]  `===`
- [ ]  `!=`
- [ ]  `!==`
- [ ]  `>`
- [ ]  `<`
- [ ]  `>=`
- [ ]  `<=`

### Operadores Lógicos

- [ ]  `&&`
- [ ]  `||`
- [ ]  `!`

### Operadores Modernos

- [ ]  Optional chaining `?.`
- [ ]  Nullish coalescing `??`
- [ ]  Ternario

### Operadores Avanzados

- [ ]  Spread operator
- [ ]  Rest operator
- [ ]  Bitwise operators
- [ ]  Operadores unarios

---

## [1.5 Estructuras de Control](./level_1/control_structure/1779400118-GDNU.md)

### Condicionales

- [ ]  `if`
- [ ]  `else`
- [ ]  `switch`

### Loops

- [ ]  `for`
- [ ]  `while`
- [ ]  `do while`
- [ ]  `for in`
- [ ]  `for of`

### Control de Flujo

- [ ]  `break`
- [ ]  `continue`
- [ ]  `return`

---

## [1.6 Funciones](./level_1/functions/1779400344-PQPC.md)

### Tipos de Funciones

- [ ]  Function declaration
- [ ]  Function expression
- [ ]  Arrow functions
- [ ]  IIFE

### Parámetros

- [ ]  Parámetros por defecto
- [ ]  Rest parameters
- [ ]  Spread en funciones

### Conceptos Avanzados

- [ ]  Closures
- [ ]  Lexical scope
- [ ]  Higher-order functions
- [ ]  Callbacks

---

## [1.7 Arrays](./level_1/arrays/1779400741-YGGO.md)

### Creación y Manipulación

- [ ]  Arrays literales
- [ ]  `Array()`
- [ ]  `Array.from()`
- [ ]  `Array.of()`

### Métodos Básicos

- [ ]  `push`
- [ ]  `pop`
- [ ]  `shift`
- [ ]  `unshift`
- [ ]  `slice`
- [ ]  `splice`

### Iteración

- [ ]  `forEach`
- [ ]  `map`
- [ ]  `filter`
- [ ]  `reduce`
- [ ]  `find`
- [ ]  `findIndex`
- [ ]  `some`
- [ ]  `every`

### Métodos Modernos

- [ ]  `flat`
- [ ]  `flatMap`
- [ ]  `sort`
- [ ]  `toSorted`
- [ ]  `toReversed`
- [ ]  `toSpliced`
- [ ]  `groupBy`

---

## [1.8 Objetos](./level_1/objects/1779400819-XGIT.md)

### Creación de Objetos

- [ ]  Object literal
- [ ]  `new Object`
- [ ]  `Object.create`

### Propiedades y Métodos

- [ ]  Dot notation
- [ ]  Bracket notation
- [ ]  Métodos

### Métodos de Object

- [ ]  `Object.keys`
- [ ]  `Object.values`
- [ ]  `Object.entries`
- [ ]  `Object.assign`
- [ ]  `Object.freeze`
- [ ]  `Object.seal`
- [ ]  `Object.hasOwn`

### Copias y Referencias

- [ ]  Shallow copy
- [ ]  Deep copy
- [ ]  `structuredClone`

### Destructuring

- [ ]  Objetos
- [ ]  Arrays

---

## [1.9 Strings](./level_1/strings/1779400860-TYYM.md)

### Métodos de Strings

- [ ]  `length`
- [ ]  `charAt`
- [ ]  `indexOf`
- [ ]  `includes`
- [ ]  `slice`
- [ ]  `substring`
- [ ]  `replace`
- [ ]  `replaceAll`
- [ ]  `split`
- [ ]  `trim`

### Template Literals

- [ ]  Interpolación
- [ ]  Multiline strings

---

## [1.10 JSON](./level_1/json/1779400902-QIIF.md)

- [ ]  `JSON.stringify`
- [ ]  `JSON.parse`
- [ ]  Serialización
- [ ]  Limitaciones del JSON

---

## [1.11 Fechas e Internacionalización](./level_1/date/1779400980-BXVY.md)

### Dates

- [ ]  `Date`
- [ ]  Timestamps
- [ ]  Parseo de fechas
- [ ]  Timezones

### Intl API

- [ ]  `Intl.NumberFormat`
- [ ]  `Intl.DateTimeFormat`
- [ ]  `Intl.RelativeTimeFormat`

---

# Nivel 2 — JavaScript Intermedio

## [2.1 Asincronía](./level_2/asincronia/asincronia.md)

### Callbacks

- [ ]  Callback functions
- [ ]  Callback hell
- [ ]  Error-first callbacks

### Promises

- [ ]  Estados de una Promise
- [ ]  `.then`
- [ ]  `.catch`
- [ ]  `.finally`

### Métodos de Promise

- [ ]  `Promise.all`
- [ ]  `Promise.race`
- [ ]  `Promise.allSettled`
- [ ]  `Promise.any`

### Async/Await

- [ ]  `async`
- [ ]  `await`
- [ ]  Manejo de errores

---

## [2.2 Event Loop (MUY IMPORTANTE)](./level_2/event_loop/event-loop.md)

- [ ]  Call Stack
- [ ]  Web APIs
- [ ]  Callback Queue
- [ ]  Microtasks
- [ ]  Macrotasks
- [ ]  Event Loop
- [ ]  Promises en el Event Loop
- [ ]  `queueMicrotask`

---

## [2.3 Timers y Scheduler APIs](./level_2/timers_schedule/schedule-timer.md)

- [ ]  `setTimeout`
- [ ]  `setInterval`
- [ ]  `requestAnimationFrame`
- [ ]  `requestIdleCallback`

---

## [2.4 This y Contexto](./level_2/this_context/this context.md)

### `this`

- [ ]  En objetos
- [ ]  En funciones
- [ ]  En arrow functions
- [ ]  En clases

### Binding

- [ ]  `call`
- [ ]  `apply`
- [ ]  `bind`

---

## [2.5 Manejo de Errores](./level_2/manejo_errores/erros.md)

- [ ]  `try/catch`
- [ ]  `finally`
- [ ]  `throw`
- [ ]  Errores personalizados

### Tipos de Errores

- [ ]  `TypeError`
- [ ]  `ReferenceError`
- [ ]  `SyntaxError`

---

## [2.6 Expresiones Regulares](./level_2/expresion_regulars/expresiones.md)

- [ ]  Sintaxis básica
- [ ]  Flags
- [ ]  `test`
- [ ]  `exec`
- [ ]  `match`
- [ ]  `replace`

---

## [2.7 Estructuras Avanzadas](./level_2/advance_structure/structure.md)

### Map

- [ ]  `set`
- [ ]  `get`
- [ ]  `has`

### Set

- [ ]  Valores únicos

### WeakMap y WeakSet

- [ ]  Garbage collection

---

## [2.8 Programación Orientada a Objetos](./level_2/poo/poo.md)

### Prototypes

- [ ]  Prototype chain
- [ ]  Herencia prototípica

### Classes

- [ ]  Constructor
- [ ]  Métodos
- [ ]  Static methods
- [ ]  Getters y setters

### Herencia

- [ ]  `extends`
- [ ]  `super`

### Encapsulación

- [ ]  Campos privados `#`

---

## [2.9 Módulos](./level_2/moduls/moduls.md)

### CommonJS

- [ ]  `require`
- [ ]  `module.exports`

### ES Modules

- [ ]  `import`
- [ ]  `export`
- [ ]  Dynamic imports

---

# Nivel 3 — JavaScript Avanzado

## 3.1 Programación Funcional

- [ ]  Inmutabilidad
- [ ]  Pure functions
- [ ]  Side effects
- [ ]  Composition
- [ ]  Currying
- [ ]  Recursión

---

## 3.2 Iteradores y Generadores

### Iterators

- [ ]  `Symbol.iterator`

### Generators

- [ ]  `function*`
- [ ]  `yield`

---

## 3.3 Symbols y Metaprogramación

### Symbols

- [ ]  Well-known symbols

### Proxy

- [ ]  Traps

### Reflect API

---

## 3.4 Memory Management

### Garbage Collection

- [ ]  Heap
- [ ]  Stack
- [ ]  Referencias

### Memory Leaks

- [ ]  Closures
- [ ]  DOM references
- [ ]  Timers

---

## 3.5 Runtime de JavaScript

- [ ]  Browser runtime
- [ ]  Node.js runtime
- [ ]  V8 Engine
- [ ]  Libuv

---

## 3.6 Streams API

- [ ]  ReadableStream
- [ ]  WritableStream
- [ ]  TransformStream

---

# Nivel 4 — JavaScript en el Navegador

## 4.1 DOM

### Selección

- [ ]  `querySelector`
- [ ]  `querySelectorAll`

### Manipulación

- [ ]  `createElement`
- [ ]  `appendChild`
- [ ]  `remove`
- [ ]  `innerHTML`
- [ ]  `textContent`

### Clases y atributos

- [ ]  `classList`
- [ ]  `setAttribute`

---

## 4.2 Eventos

- [ ]  `addEventListener`
- [ ]  Event object
- [ ]  Bubbling
- [ ]  Capturing
- [ ]  Delegation
- [ ]  `preventDefault`
- [ ]  `stopPropagation`

---

## 4.3 BOM

- [ ]  `window`
- [ ]  `navigator`
- [ ]  `location`
- [ ]  `history`

---

## 4.4 Storage

- [ ]  `localStorage`
- [ ]  `sessionStorage`
- [ ]  Cookies
- [ ]  IndexedDB
- [ ]  Cache API

---

## 4.5 Fetch API y AJAX

### Fetch

- [ ]  GET
- [ ]  POST
- [ ]  PUT
- [ ]  DELETE

### Headers y JSON

- [ ]  Headers
- [ ]  JSON parsing

### AbortController

- [ ]  Cancelación de requests

---

## 4.6 APIs Modernas del Navegador

- [ ]  Clipboard API
- [ ]  Intersection Observer
- [ ]  Resize Observer
- [ ]  Mutation Observer
- [ ]  Geolocation API
- [ ]  Notifications API
- [ ]  Web Workers

---

## 4.7 Web Components

- [ ]  Shadow DOM
- [ ]  Custom Elements
- [ ]  Templates

---

## 4.8 Service Workers y PWA

- [ ]  Service Workers
- [ ]  Cache strategies
- [ ]  Offline support
- [ ]  PWA basics

---

# Nivel 5 — Performance y Optimización

## 5.1 Rendering del Navegador

- [ ]  Critical Rendering Path
- [ ]  Reflow
- [ ]  Repaint
- [ ]  Layout thrashing
- [ ]  Compositing

---

## 5.2 Optimización

- [ ]  Debounce
- [ ]  Throttle
- [ ]  Lazy loading
- [ ]  Code splitting
- [ ]  Memoization

---

## 5.3 Performance Web

- [ ]  Lighthouse
- [ ]  Web Vitals
- [ ]  Optimización de rendering
- [ ]  Optimización de loops

---

# Nivel 6 — Seguridad en JavaScript

## 6.1 Seguridad Web

- [ ]  XSS
- [ ]  CSRF
- [ ]  CORS
- [ ]  CSP

---

## 6.2 Seguridad Frontend

- [ ]  Sanitización
- [ ]  Tokens
- [ ]  Seguridad en LocalStorage

---

# Nivel 7 — Tooling Moderno

## 7.1 Package Managers

- [ ]  npm
- [ ]  yarn
- [ ]  pnpm

---

## 7.2 Bundlers

- [ ]  Vite
- [ ]  Webpack
- [ ]  Rollup
- [ ]  ESBuild

---

## 7.3 Transpilación

- [ ]  Babel
- [ ]  Polyfills

---

## 7.4 Calidad de Código

- [ ]  ESLint
- [ ]  Prettier
- [ ]  Husky
- [ ]  Lint-staged

---

# Nivel 8 — Testing

## 8.1 Testing Fundamentals

- [ ]  Unit testing
- [ ]  Integration testing
- [ ]  Mocking

---

## 8.2 Herramientas

- [ ]  Jest
- [ ]  Vitest
- [ ]  Testing Library

---

## 8.3 Cobertura y Calidad

- [ ]  Coverage
- [ ]  TDD básico

---

# Nivel 9 — TypeScript

## 9.1 Fundamentos

- [ ]  Tipos básicos
- [ ]  Interfaces
- [ ]  Types
- [ ]  Union types
- [ ]  Type narrowing

---

## 9.2 TypeScript Avanzado

- [ ]  Generics
- [ ]  Utility types
- [ ]  Conditional types
- [ ]  Mapped types
- [ ]  Infer
- [ ]  Decorators

---

# Nivel 10 — Arquitectura Frontend

## 10.1 Arquitectura

- [ ]  Modularidad
- [ ]  Separación de responsabilidades
- [ ]  Clean Architecture frontend

---

## 10.2 State Management

- [ ]  Estado global
- [ ]  Estado local
- [ ]  Flujo de datos

---

## 10.3 Reactive Programming

- [ ]  Observables
- [ ]  Subjects
- [ ]  Operators
- [ ]  `switchMap`
- [ ]  `mergeMap`
- [ ]  `concatMap`
- [ ]  `exhaustMap`
- [ ]  `debounceTime`
- [ ]  `takeUntil`

---

# Nivel 11 — Patrones de Diseño

## Patrones Clásicos

- [ ]  Singleton
- [ ]  Factory
- [ ]  Observer
- [ ]  Adapter
- [ ]  Module Pattern
- [ ]  Dependency Injection
- [ ]  Pub/Sub

---

# Nivel 12 — Node.js Básico

## Core Modules

- [ ]  `fs`
- [ ]  `path`
- [ ]  `process`
- [ ]  `os`

---

## Backend Básico

- [ ]  Variables de entorno
- [ ]  Streams
- [ ]  EventEmitter

---

# Nivel 13 — Proyectos Reales (OBLIGATORIO)

## Proyectos Iniciales

- [ ]  Todo App
- [ ]  Calculadora
- [ ]  CRUD Vanilla JS
- [ ]  Weather App

---

## Proyectos Intermedios

- [ ]  Kanban Board
- [ ]  Chat realtime
- [ ]  Infinite Scroll
- [ ]  Drag & Drop App

---

## Proyectos Avanzados

- [ ]  Mini framework reactivo
- [ ]  Virtual DOM básico
- [ ]  Sistema de routing
- [ ]  Fetch wrapper
- [ ]  Clone básico de RxJS
- [ ]  PWA completa

---

# Nivel 14 — Preparación Profesional

## Entrevistas

- [ ]  Event Loop profundo
- [ ]  Closures
- [ ]  Prototype chain
- [ ]  Async JavaScript
- [ ]  Performance
- [ ]  Seguridad

---

## Buenas Prácticas

- [ ]  Clean Code
- [ ]  SOLID aplicado a frontend
- [ ]  Escalabilidad
- [ ]  Mantenibilidad

<!-- ### 4.2 TypeScript (Opcional pero recomendado) -->
<!---->
<!-- - [ ] **Conceptos básicos** -->
<!--   - Tipos estáticos -->
<!--   - Interfaces -->
<!--   - Type aliases -->
<!--   - Generics -->
<!---->
<!-- - [ ] **Integración con JavaScript** -->
<!---->
<!-- ### 4.3 Web APIs Modernas -->
<!---->
<!-- - [ ] **Service Workers** -->
<!--   - PWA (Progressive Web Apps) -->
<!---->
<!-- - [ ] **Web Workers** -->
<!--   - Threading en JavaScript -->
<!---->
<!-- - [ ] **WebSockets** -->
<!--   - Comunicación en tiempo real -->
<!---->
<!-- - [ ] **Canvas API** -->
<!--   - Gráficos 2D -->
<!---->
<!-- - [ ] **Geolocation API** -->
<!---->
<!-- - [ ] **Notification API** -->
<!---->
<!-- ### 4.4 Testing -->
<!---->
<!-- - [ ] **Tipos de testing** -->
<!--   - Unit testing -->
<!--   - Integration testing -->
<!--   - E2E testing -->
<!---->
<!-- - [ ] **Frameworks de testing** -->
<!--   - Jest -->
<!--   - Mocha + Chai -->
<!--   - Vitest -->
<!---->
<!-- - [ ] **Testing en el navegador** -->
<!--   - Cypress -->
<!--   - Playwright -->
<!---->
<!-- ### 4.5 Build Tools y Module Bundlers -->
<!---->
<!-- - [ ] **Package Managers** -->
<!--   - npm -->
<!--   - yarn -->
<!--   - pnpm -->
<!---->
<!-- - [ ] **Bundlers** -->
<!--   - Webpack -->
<!--   - Vite -->
<!--   - Parcel -->
<!--   - Rollup -->
<!---->
<!-- - [ ] **Transpilers** -->
<!--   - Babel -->
<!---->
<!-- - [ ] **Linters** -->
<!--   - ESLint -->
<!--   - Prettier -->
<!---->
<!-- --- -->
<!---->
<!-- ## Nivel 5: Especialización -->
<!---->
<!-- ### 5.1 Frontend Frameworks -->
<!---->
<!-- Elige uno para especializarte: -->
<!---->
<!-- - [ ] **React** -->
<!--   - Components -->
<!--   - JSX -->
<!--   - Hooks -->
<!--   - Context API -->
<!--   - React Router -->
<!---->
<!-- - [ ] **Vue.js** -->
<!--   - Vue components -->
<!--   - Directives -->
<!--   - Vue Router -->
<!--   - Vuex/Pinia -->
<!---->
<!-- - [ ] **Angular** -->
<!--   - TypeScript -->
<!--   - Components -->
<!--   - Services -->
<!--   - RxJS -->
<!---->
<!-- ### 5.2 Backend con JavaScript -->
<!---->
<!-- - [ ] **Node.js** -->
<!--   - Event Loop -->
<!--   - File System -->
<!--   - Streams -->
<!--   - Buffer -->
<!---->
<!-- - [ ] **Frameworks de Backend** -->
<!--   - Express.js -->
<!--   - NestJS -->
<!--   - Fastify -->
<!--   - Koa -->
<!---->
<!-- - [ ] **Bases de datos** -->
<!--   - MongoDB (NoSQL) -->
<!--   - PostgreSQL (SQL) -->
<!--   - ORMs: Sequelize, Prisma -->
<!---->
<!-- ### 5.3 Rendimiento y Optimización -->
<!---->
<!-- - [ ] **Performance** -->
<!--   - Code splitting -->
<!--   - Lazy loading -->
<!--   - Memoization -->
<!--   - Debouncing y Throttling -->
<!---->
<!-- - [ ] **Métricas** -->
<!--   - Lighthouse -->
<!--   - Web Vitals -->
<!---->
<!-- - [ ] **Debugging** -->
<!--   - Chrome DevTools -->
<!--   - Node.js debugger -->
<!---->
<!-- ### 5.4 Seguridad -->
<!---->
<!-- - [ ] **Conceptos importantes** -->
<!--   - XSS (Cross-Site Scripting) -->
<!--   - CSRF (Cross-Site Request Forgery) -->
<!--   - SQL Injection -->
<!--   - Autenticación y autorización -->
<!--   - JWT (JSON Web Tokens) -->
<!--   - OAuth -->
<!---->
<!-- ### 5.5 Design Patterns -->
<!---->
<!-- - [ ] **Patrones comunes** -->
<!--   - Module Pattern -->
<!--   - Singleton -->
<!--   - Factory -->
<!--   - Observer -->
<!--   - Decorator -->
<!--   - MVC/MVVM -->
<!---->
<!-- --- -->
<!---->
<!-- ## 📖 Recursos Recomendados -->
<!---->
<!-- ### Documentación Oficial -->
<!-- - [MDN Web Docs - JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript) -->
<!-- - [JavaScript.info](https://javascript.info/) -->
<!-- - [ECMAScript Specification](https://tc39.es/ecma262/) -->
<!---->
<!-- ### Cursos y Tutoriales -->
<!-- - freeCodeCamp -->
<!-- - The Odin Project -->
<!-- - Eloquent JavaScript (libro gratuito) -->
<!---->
<!-- ### Práctica -->
<!-- - [Exercism](https://exercism.org/tracks/javascript) -->
<!-- - [CodeWars](https://www.codewars.com/) -->
<!-- - [LeetCode](https://leetcode.com/) -->
<!-- - [HackerRank](https://www.hackerrank.com/) -->
<!---->
<!-- ### Comunidades -->
<!-- - Stack Overflow -->
<!-- - Reddit: r/javascript, r/learnjavascript -->
<!-- - Discord: JavaScript, The Odin Project -->
<!---->
<!-- --- -->
<!---->
<!-- ## 🎯 Plan de Estudio Sugerido -->
<!---->
<!-- ### Fase 1 (1-2 meses): Fundamentos -->
<!-- - Variables, tipos de datos, operadores -->
<!-- - Estructuras de control -->
<!-- - Funciones, arrays, objetos -->
<!-- - **Proyecto**: Calculadora simple -->
<!---->
<!-- ### Fase 2 (2-3 meses): Intermedio -->
<!-- - DOM manipulation -->
<!-- - Asincronía (Promises, async/await) -->
<!-- - Fetch API -->
<!-- - **Proyecto**: To-Do App con localStorage -->
<!---->
<!-- ### Fase 3 (2-3 meses): Avanzado -->
<!-- - OOP y Prototypes -->
<!-- - Programación funcional -->
<!-- - ES6+ features -->
<!-- - **Proyecto**: Weather App usando API -->
<!---->
<!-- ### Fase 4 (3-4 meses): Especialización -->
<!-- - Elige frontend (React/Vue) o backend (Node.js) -->
<!-- - Testing -->
<!-- - Build tools -->
<!-- - **Proyecto**: Full-stack app (MERN/MEAN stack) -->
<!---->
<!-- --- -->
<!---->
<!-- ## ✅ Checklist de Progreso -->
<!---->
<!-- Usa este checklist para marcar tu progreso: -->
<!---->
<!-- - [ ] Completado Nivel 1: Fundamentos Esenciales -->
<!-- - [ ] Completado Nivel 2: Conceptos Intermedios -->
<!-- - [ ] Completado Nivel 3: Conceptos Avanzados -->
<!-- - [ ] Completado Nivel 4: JavaScript Moderno -->
<!-- - [ ] Completado Nivel 5: Especialización -->
<!-- - [ ] Primer proyecto personal completado -->
<!-- - [ ] Segundo proyecto personal completado -->
<!-- - [ ] Tercer proyecto personal completado -->
<!-- - [ ] Portfolio online creado -->
<!-- - [ ] Primera contribución a Open Source -->
<!---->
<!-- --- -->
<!---->
<!-- ## 💡 Consejos Finales -->
<!---->
<!-- 1. **Practica constantemente** - La teoría sin práctica no sirve -->
<!-- 2. **Construye proyectos** - Aprende haciendo -->
<!-- 3. **Lee código de otros** - GitHub, Open Source -->
<!-- 4. **Únete a comunidades** - Pregunta, ayuda, comparte -->
<!-- 5. **No te rindas** - JavaScript toma tiempo, sé paciente -->
<!-- 6. **Documenta tu aprendizaje** - Blog, notas, este roadmap -->
<!---->
<!-- --- -->
<!---->
<!-- **¡Mucha suerte en tu viaje aprendiendo JavaScript! 🚀** -->
<!---->
<!-- --- -->

_Última actualización: Febrero 2026_
_Basado en: MDN Web Docs, roadmap.sh, y mejores prácticas de la comunidad_
