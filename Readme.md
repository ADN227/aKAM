# Monitoreo de recursos de Azure 
![](https://akncus.blob.core.windows.net/git/8/K_048.jpg)

Para usar el recurso **Azure Monitor** necesitamos crear un recurso de Azure a monitorear. En este caso crearemos una máquina virtual conectada por RDP para monitorear el uso de CPU.
![](https://akncus.blob.core.windows.net/git/8/K_047.jpg)

Para conectarnos a la máquina virtual, usamos un archivo de configuración de tipo .rdp que recibimos al crear la máquina virtual. 
![](https://akncus.blob.core.windows.net/git/8/K_050.jpg)

## Uso de **Monitor**
Podemos ver el uso de CPU de la máquina virtual en la sección **Métricas**. En esta sección llenamos los datos que corresponden a la máquina virtual.
![](https://akncus.blob.core.windows.net/git/8/K_051.jpg)

Para recibir correos electrónicos cuando la máquina virtual se encuentre en estado alerta, creamos una **Regla de alertas** en la sección **Alertas**.
![](https://akncus.blob.core.windows.net/git/8/K_055.jpg)

Al crear la regla de alertas:

- **Ámbito**: Seleccionamos la máquina virtual a monitorear.
- **Condición**: Seleccionamos la condición que queremos que se cumpla para que se envíe el correo electrónico.
- **Deatalles**: Seleccionamos el tipo de alerta que queremos que se envíe.

![](https://akncus.blob.core.windows.net/git/8/K_057.jpg)

En la sección **Alertas** podemos ver la regla de alertas creada, ademas podemos ver el estado de la regla. Mientras que en nuestro correo 
![](https://akncus.blob.core.windows.net/git/8/K_064.jpg)
