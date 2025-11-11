# ⚙️ Cambios en la operativa de Eclipse ERP conforme a la normativa Veri*Factu

Con la entrada en vigor de la normativa **Veri*Factu (Real Decreto 1007/2023)**, **Eclipse ERP** ha incorporado una serie de adaptaciones en su funcionamiento para garantizar el cumplimiento de los principios de **integridad, trazabilidad e inalterabilidad** de los registros de facturación.

---

## 1. 🧾 Inalterabilidad de facturas

Una vez emitidas, las facturas **no pueden ser modificadas**.

No obstante, se permite editar ciertos **campos no relevantes fiscalmente**, como notas internas, direcciones de envío, rutas o estados, siempre que no afecten a los datos fiscales o contables de la factura.

---

## 2. ✍️ Incorporación del concepto de borrador de factura

El **borrador de factura** es una versión **previa y editable** que permite al usuario **revisar y completar los datos** antes de su emisión definitiva.

Durante esta fase:
- No se asigna **número de factura**, **fecha de emisión** ni **huella de registro (hash)**.  
- No se genera ningún **registro Veri*Factu** ni se realiza comunicación con la **AEAT**.

Cuando el usuario valida el borrador y **emite la factura**, esta pasa a ser **definitiva e inalterable**, cumpliendo plenamente con los requisitos de la **normativa Veri*Factu**.

---

## 3. 🧍‍♂️ Identificación obligatoria del cliente

Para la emisión de **facturas ordinarias**, es obligatorio indicar el **NIF del cliente**.  
En caso de clientes no identificados, deberán emitirse **facturas simplificadas**.

---

## 4. 🔒 Datos fiscales del cliente inmodificables

Una vez se haya emitido una factura asociada a un cliente, los campos **nombre fiscal**, **NIF** y **país** **no podrán modificarse**.  
Si es necesario cambiar estos datos, deberá **crearse un nuevo cliente**.

---

## 5. 🔢 Numeración y fechas correlativas

Las facturas deben mantener una **numeración y fechas estrictamente correlativas**.  
Los **numeradores son automáticos** y no pueden modificarse manualmente.

---

## 6. ✅ Validación de datos conforme a normativa

Antes de emitir una factura, **Eclipse ERP valida automáticamente los datos** según los criterios establecidos por la normativa **Veri*Factu**, ayudando a **prevenir errores o inconsistencias** antes del registro definitivo.

---

## 7. 📅 Restricción de fechas

No es posible emitir facturas con una **fecha posterior al día actual**, garantizando la coherencia temporal y la integridad de los registros de facturación.

---