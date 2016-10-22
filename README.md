# BPMN

| **Proyecto** | **Versión**  |  **Autor**  |
|--------------|--------------|-------------|
|bpmn          |1.0.0         |Dilan Zúniga|



## Descripción

Repositorio en el cual encontraremos un ejemplo BPMN .


## Instrucciones

Encontramos 1 piscina llamada "Proceso Para Solicitud de Bodega" el cual tenemos 3 carriles ( Ventas, bodega, adquisición).

Se inicia en el departamento de ventas, generan una solicitud que luego pasa a una pasarela exclusiva en el carril de bodega raelizando la pregunta de ¿Esta en stock?.

Si la respuesta es positiva, se **retira de bodega y despacha** para luego **entragar al cliente** que a continuación este [termina] el proceso; a su vez en bodega se raliza otra pasarela exclusiva en el cual se preguntan **¿Quedan suficiente en stock?** si la respuesta es positiva este **termina** el proceso en bodega, si la respuesta es negativa pasa a una pasarela que leugo **generan una solicitud de compra** para trasladarse a la pasarela de adquisición para **procesar la solicitud de compra** y luego [terminar] el proceso.

Si la respuesta es negativa pasa a una pasarela que luego generan una solicitud de comprp para trasladarse a la pasarela de adquisición para procesar la solicitud de compra y luego terminar el proceso.

## Puntos de mejora de BPMN 
*LA mejora principal a agregarle es la integración de los procesos ya que terminan muy drásticamente.

*Agregarle notación al principio y al final de cada carril.

