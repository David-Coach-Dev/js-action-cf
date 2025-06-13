# JS-ACTION-CF

## Ejemplo: Hello world javascript action

Esta acción imprime "Hello World" o "Hello" + el nombre de una persona a saludar en el log.

### Entradas

| Entrada         | Descripción                              | Requerido | Predeterminado |
|-----------------|------------------------------------------|-----------|---------------|
| who-to-greet    | El nombre de la persona a saludar        | Sí        | World         |

### Salidas

| Salida | Descripción                        |
|--------|------------------------------------|
| time   | La hora en la que se realizó el saludo |

### Ejemplo de uso

```yaml
uses: actions/js-act6ion-cfn@v1.0
with:
  who-to-greet: 'Mona the Octocat'
```
