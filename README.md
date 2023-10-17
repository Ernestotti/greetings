# Saludos en Go

Este paquete proporciona una forma simple de obtener saludos personalizados en Go.

## Instalación

Para instalar este paquete, utiliza el siguiente comando:
```bash
go get github.com/Ernestotti/greetings
```

### Uso básico

Aquí tienes un ejemplo de como utilizar el paquete en tu codigo:

```go
package main

import (
    "fmt"
    "github.com/Ernestotti/greetings"
)
func main() {
    message, err := greetings.Hello("Ernesto")
    
    if err != nil {
        fmt.Println("Ocurrió un error:", err)
        return
    }

    fmt.Println(message)
} 

```
Este ejemplo importa el paquete github.com/Ernestotti/greetings y llama a la función Hello para realizar un 
saludo personalizado. Si ocurre un error, se imprime un mensaje de error.
