# Triggers - Ejercicio 3

## Configura un workflow para que se ejecute cuando se cree una nueva Issue

Crear el workflow:

![](../../datos/trigger_ej3_foto1.png)

El trigger para cuando se cree una nueva issue es:

```yaml
on:
  issues:
    types: [opened]
```

Subir el workflow a la rama main:

![](../../datos/trigger_ej3_foto4.png)

Crear la issue:

![](../../datos/trigger_ej3_foto2.png)

![](../../datos/trigger_ej3_foto3.png)

Comprobar que funcina:

![](../../datos/trigger_ej3_foto5.png)