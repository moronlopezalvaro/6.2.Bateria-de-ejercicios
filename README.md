# 6.2.Bateria de ejercicios

Ejercicio 1
```mermaid
classDiagram
    class Usuario {
        - String nombreUsuario
        - String contraseña
        + String correo
        + cambiarPassword(String nueva)
        - validarEmail()
    }
```

Ejercicio 2
```mermaid
classDiagram
    class Persona {
        String nombre
        String DNI
    }

    class Estudiante {
        String numeroExpediente
        float notaMedia
    }

    Persona <|-- Estudiante
```
