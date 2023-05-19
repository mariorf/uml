# UML

# Diagrama Flujo

```mermaid

---
title: Login
---

flowchart TD
    A[IntroducirCampos] --> B(Submit)
    B --> C{Validar}
    C -->|CorreoNoExiste| A
    C -->|Contraseña incorrecta| A
    C -->|UsuarioNoRegistrado| D[QuiereRegistrarse?] -->E[MostrarVentanaRegistro]
  

