# Variables y Outputs - Ejercicio 2

## Configura un job que use un secreto definido en el repositorio (por ejemplo, MY_SECRET) y lo use en un comando.

Crear un secreto:

![](../../datos/variables_ej2_foto1.png)

![](../../datos/variables_ej2_foto2.png)

![](../../datos/variables_ej2_foto3.png)

Workflow:

![](../../datos/variables_ej2_foto4.png)

Para llamar al secreto uso:

```yaml
${{ secrets.MY_SECRET }}
```

Resultado:

![](../../datos/variables_ej2_foto5.png)