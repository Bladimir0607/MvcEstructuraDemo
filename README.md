# 🧩 MvcEstructuraDemo

## 📌 Descripción

Proyecto base creado con **ASP.NET Core Web App (Model-View-Controller)** en Visual Studio 2022.

El objetivo es familiarizarse con la estructura de un proyecto MVC y ejecutar la aplicación en entorno local.

---

## 🏗 Estructura del Proyecto

El proyecto incluye las siguientes carpetas principales:

- **Controllers** → Contiene los controladores (HomeController).
- **Models** → Contiene clases de modelo (ErrorViewModel).
- **Views** → Contiene las vistas Razor (.cshtml).
- **wwwroot** → Archivos estáticos (CSS, JS, Bootstrap).
- **Program.cs** → Configuración principal del proyecto.

---

## ▶️ Ejecución Local

Al ejecutar el proyecto, la aplicación corre en: https://localhost:7209

(El puerto puede variar según la configuración del entorno.)

---

## 🔄 Flujo MVC

1. El navegador accede a la URL.
2. El enrutamiento dirige la solicitud a `HomeController`.
3. El método `Index()` devuelve la vista correspondiente.
4. La vista se renderiza utilizando `_Layout.cshtml`.

---

## 🎯 Objetivo Académico

Explorar y comprender la estructura básica de un proyecto ASP.NET Core MVC.

---

## 👤 Autor

Bladimir Ventura
