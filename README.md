# WebPay - WooCommerce
Corrección de errores / ajustes en plugin WebPay para WooCommerce.<br>

* **Correcciones a versión:** 2.0.4
* El plugin oficial lo puedes encontrar en: http://www.transbankdevelopers.cl/<br>


> ## Correcciones
* Varias llamadas a atributos de clases cambiadas a métodos.
* Ajuste a la llamada SOAP: el ambiente de integración tiene problemas con el certificado de seguridad, por lo que se realiza un bypass a la verificación del SSL en SOAP (**Actualizado al: 04/09/2018**)
* healthcheck.php realiza una llamada a la última versión a la API de Github. Arroja advertencia por el límite de consultas, por lo que se devuelve un string fijo. Aún pendiente de corrección.
* Ajuste en verificación de página actual del administrador para insertar integration.js


En general son esos ajustes, puede haber otro que no haya anotado. La verdad, son varios los errores que hubo que corregir y no llevé el registro exacto.

# ¡Son tod@s libres de aportar!
