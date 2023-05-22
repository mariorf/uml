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


# Diagrama Estado

```mermaid

stateDiagram-v2
    Idle --> Moving
    Idle --> Jumping
    Idle --> Crouching
    Moving --> Idle
    Moving --> Crouching
    Crouching --> Idle
    Crouching --> Jumping
    Crouching --> Crawlng

