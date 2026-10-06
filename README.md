# Pulso de Compras México

Tablero semanal de inteligencia de mercado para compras de construcción (GNFR) en México: precio estimado de estructura metálica por kg, índices INEGI por categoría, tipo de cambio, riesgos y noticias.

## Cómo se ve

Abre `index.html` desde GitHub Pages. La página lee las series mensuales de `data/series.json`. 

## Datos

- **INEGI**: Índice Nacional de Precios Productor (boletines mensuales) e informes CMIC CEICO con datos INEGI. Para acero solo se usa INEGI.
- **Estructura Metálica (MXN/kg)**: precio de mercado estimado de suministro, fabricación, flete y montaje, movido mes a mes con la variación de construcción de INEGI ajustada al índice de naves y plantas industriales.
- **Banxico**: tipo de cambio FIX.

Es una referencia de mercado, no una cotización. Los precios que paga el equipo de compras no se publican aquí.
