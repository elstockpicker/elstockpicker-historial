# El Stock Picker · Histórico público

Cada idea publicada queda registrada aquí y no se edita: sólo se agregan filas.

- `eventos.csv`: bitácora de cada idea (publicada, entrada, cambio de estado, alerta, cerrada, corrección).
- `precios.csv`: cierres diarios de cada idea y del SPY.
- `index.html`: la página del histórico (GitHub Pages), regenerada cada día hábil.

Reglas: una idea publicada EN ZONA DE COMPRA entra al cierre del día de publicación; una idea publicada
ESPERANDO PRECIO entra al primer cierre dentro de la zona y, si en 12 meses no entra, se cierra "sin entrada".
Rendimientos totales con cierres ajustados por dividendos, contra el SPY en el mismo periodo.

Contenido educativo, no es recomendación personalizada.
