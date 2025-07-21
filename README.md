# 🛰️ Microservicio: client-service

Este microservicio, desarrollado con NestJS, se conecta al microservicio `time-service` usando protocolo TCP y solicita la hora actual.

---

## 📦 Requisitos

- Node.js (v18+)
- NestJS CLI (`npm install -g @nestjs/cli`)

---

## ⚙️ Instalación

```bash
npm install
```
---

## ▶️ Ejecución
```bash
npm run start
```
---

Este cliente se conectará al microservicio time-service en localhost:3001 y mostrará en consola la hora actual recibida.

---

## 📂 Estructura
main.ts: conecta al servidor TCP y envía la solicitud.

app.module.ts: módulo raíz requerido por NestJS.