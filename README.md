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
        + String nombre
        + String DNI
    }

    class Estudiante {
        + String numeroExpediente
        + float notaMedia
    }

    Persona <|-- Estudiante
```

Ejercicio 3
```mermaid
classDiagram
    class Computadora
    class PlacaBase
    class Raton

    %% Composición (vínculo fuerte)
    Computadora *-- PlacaBase : contiene

    %% Agregación (vínculo débil)
    Computadora o-- Raton : usa
```

Ejercicio 4
```mermaid
classDiagram
    class CentroComercial
    class Tienda

    CentroComercial "1" --> "1..*" Tienda : alberga
```
