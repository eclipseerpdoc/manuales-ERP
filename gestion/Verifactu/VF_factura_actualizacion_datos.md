# 🧾 Actualización de datos fiscalmente no relevantes en facturas emitidas

Según el **Reglamento Veri*Factu (Real Decreto 1007/2023)**, **no se permite modificar ningún dato relevante de una factura una vez emitida**, ya que el objetivo principal de la normativa es garantizar la **integridad**, **trazabilidad** e **inalterabilidad** de los registros de facturación.

Sin embargo, sí es posible modificar determinados **campos no relevantes fiscalmente**, siempre que se cumplan las siguientes condiciones:

---

## ✅ Condiciones para la actualización

- No deben afectar al contenido fiscal de la factura (por ejemplo: base imponible, tipo de IVA, importe total, serie, número, fecha de emisión o datos del emisor/receptor).  
- No deben alterar el **registro de facturación generado** ni la **huella digital asociada**.  
- No debe modificarse el **archivo original** de la factura, sino que únicamente se actualizarán **metadatos o campos auxiliares** en el sistema ERP.

> ⚠️ **Importante:**  
> Si el campo forma parte del contenido visible de la factura, lo más seguro y conforme a normativa es emitir una **factura rectificativa**.

---

## 🛠️ Cómo actualizar datos no relevantes en *eclipseERP*

1. Accede a la **ventana de facturas emitidas**.  
2. Selecciona la factura que deseas actualizar.  
3. Pulsa sobre el botón **“Ver”** en la columna de opciones disponibles.  
4. Se mostrará la factura con todos los **datos fiscalmente relevantes bloqueados**, y sólo se habilitarán los **campos editables permitidos**.

![Botón ver](ruta/boton_ver.png)

---

## ✏️ Campos que pueden ser editados

- **Usuario**  
- **Forma de pago**  
- **Grupo de gasto / Centro de coste**  
- **Proyecto asociado**  
- **Ruta logística o comercial**  
- **Vehículo**  
- **Conductor**  
- **Agencia de transporte**  
- **Datos de tracking**  
- **Notas internas y externas**  
- **Estado del documento**  
- **Fecha y hora de alerta**  
- **Oportunidad comercial asociada**  
- **Campos personalizados y etiquetas de clasificación**  
- **Cuenta bancaria de cargo**  
- **Cuenta contable de ventas**  
- **Mostrar o no en cuenta de explotación**  
- **Marca de contabilizado**

---

## 💾 Guardar los cambios

Para confirmar y guardar las modificaciones realizadas, pulsa el botón:

> **🟢 “Fra emitida: Actualizar sólo cabecera”**

![Botón Actualizar cabecera](ruta/boton_actualizar_cabecera.png)

---

> ℹ️ Esta funcionalidad permite mantener actualizada la información operativa y de gestión de las facturas, sin comprometer la integridad de los registros fiscales exigida por el sistema **Veri*Factu**.