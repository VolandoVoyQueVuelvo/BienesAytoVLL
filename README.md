# Bienes de los concejales · Ayuntamiento de Valladolid

Página web (pensada para móvil) que muestra el patrimonio declarado por los concejales del Ayuntamiento de Valladolid: inmuebles, depósitos, planes de pensiones, acciones y fondos, vehículos y otros bienes.

## Contenido

- `index.html`: la web. Es un único archivo sin dependencias que se puede abrir directamente en el navegador. Permite buscar por concejal, filtrar por grupo (PP, PSOE, VOX, VTLP) y ver la ficha de cada persona.
- `transparencia_VLL.xlsx`: hoja de cálculo de transparencia.

## Fuente

Declaraciones de bienes publicadas en la web del Ayuntamiento de Valladolid. El grupo político de cada concejal se dedujo de la ubicación del documento.

## Cómo se calcula

- El total de cada persona es la suma del valor de su participación en cada inmueble (valor catastral por porcentaje de propiedad) más los importes de los demás bienes.
- El valor catastral **no** es el valor de mercado.
- Las cargas (hipotecas, préstamos) se muestran aparte y **no** se restan del total.
- Las partidas sin valor en la declaración no suman al total. Los inmuebles sin porcentaje se cuentan al 100 %.
