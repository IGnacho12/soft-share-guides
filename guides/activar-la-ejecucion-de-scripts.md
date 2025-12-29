---
id: activar-la-ejecucion-de-scripts
title: Activar la ejecución de scripts W11 y W10
description: Soluciona el problema "No se puede cargar el archivo X porque la ejecución de scripts está deshabilitada en este sistema"
cover: https://i.ytimg.com/vi/hRrXrrnxdTg/maxresdefault.jpg
---

Para poder ejecutar scripts en PowerShell, es necesario cambiar la política de ejecución para permitirlo.

---

## Pasos para activar la ejecución de scripts

1. Abre **PowerShell** como **administrador**.
2. Copia y pega el siguiente comando y presiona Enter:

```powershell
Set-ExecutionPolicy Unrestricted
```

Y listo, una vez se ejecute, ya puedes cerrar la ventana, y la ejecución de scripts estará activada.
