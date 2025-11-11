# 🧾 ¿Qué hacer si una factura enviada contiene errores? 

---

Durante el envío de un **registro de facturación**, la **Agencia Tributaria** puede detectar errores en los datos de la factura (por ejemplo, NIF incorrecto, fechas incoherentes o importes no válidos).  
En estos casos, la factura será **rechazada** y deberá ser **subsanada** por el emisor.

---

## 🔔 Aviso de facturas con error

**eclipseERP** muestra automáticamente un aviso en la **pantalla de inicio**, mediante una **franja roja** que indica el número total de facturas que requieren revisión.  

![Aviso de facturas con error](ruta/aviso_facturas_error.png)

Al hacer clic sobre dicha franja, se abrirá la ventana de **Facturas**, ya filtrada para mostrar únicamente aquellas con **errores no subsanados**.

![Listado de facturas con errores](ruta/listado_facturas_error.png)

---

## 🧾 Visualización del error

En cada factura rechazada, el sistema registra el **código de error** y su **descripción**, tal como han sido devueltos por la Agencia Tributaria.  

![Detalle del error en factura](ruta/detalle_error_factura.png)

Al seleccionar una factura en la lista, estos datos se muestran en la parte inferior de la ventana, permitiendo identificar fácilmente el motivo del rechazo.

---

## 🔄 Cómo subsanar los errores

Una vez que una factura ha sido emitida y registrada bajo el sistema **Veri*Factu**, **no puede modificarse ni eliminarse**.  
La **única forma válida de corrección** es mediante la emisión de una **factura rectificativa**, en la que se referencie la factura original y se corrijan los datos erróneos.

### Pasos para subsanar:
1. Emitir la correspondiente **factura rectificativa**.  
2. Enviar el nuevo registro a la **Agencia Tributaria**.  
3. Una vez subsanado el error, pulsar el botón **“Subsanar”** en *eclipseERP* para marcar la factura original como corregida.

![Botón Subsanar](ruta/boton_subsanar.png)

---

## 📋 Seguimiento de facturas subsanadas

Desde esta misma ventana podrás consultar también las **facturas ya subsanadas**, junto con la **información interna** de cada una:

- **Usuario** que realizó la subsanación.  
- **Fecha** en la que se marcó como corregida.  

![Historial de subsanaciones](ruta/historial_subsanaciones.png)

De este modo, se mantiene un historial completo y trazable del proceso de corrección, conforme a la normativa **Veri*Factu**.