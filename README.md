# VALIDAR-CONTRATO-FLANDES

Web pública que valida el QR de la **certificación del contrato** (código CCPS#####) de la Alcaldía de Flandes
y deja descargar el PDF original de la certificación.
Reemplaza a `validacion-certificado`, que queda redirigiendo aquí para que los QR ya impresos sigan funcionando.

- Lee UNA ficha en Firestore (`flandes-avisos`, colección `certificados`). No llama a Apps Script.
- La ficha y el PDF los guarda FLANDES-CORE (Validar.gs) cada vez que se saca una certificación.
- Copyright © Oscar Polania · Experto en soluciones digitales
