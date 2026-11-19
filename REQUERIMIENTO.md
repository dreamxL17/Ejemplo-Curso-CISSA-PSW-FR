# Proyecto de Cafetería

## Reglas de Negocio (RN)
    - RN-001: Un cajero no puede vender un producto del cual no haya existencia o que no esté disponible por el momento. 

    - RN-002: Si un ingrediente clave está agotado (eje. leche de almendra), el sistema debe bloquear o marcar como no disponible ese modificador en tiempo real.

## Criterio de Aceptación (AC)
    - AC-001 Dado que un cliente selecciona un Latte y agrega un shot extra de espresso, cuando confirma la personalización, entonces el precio del ítem se actualiza sumando el costo del shot y se refleja en el subtotal.

    - AC-002 Dado que el inventario de leche de avena llega a 0, cuando un cajero o cliente intenta seleccionarla, entonces la opción aparece deshabilitada y no permite agregarse a la orden.