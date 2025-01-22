# Resumen de los cambios realizados en el Colab Template

## 1. Cambio de Técnica de Machine Learning  
Se reemplazó **Regresión Lineal** por **Bayesian Ridge Regression** para mejorar la predicción de precios.

## 2. Cambio de Mercado  
Se cambió el mercado de **NASDAQ-100** a **S&P 500**.

## 3. Selección de Activos  
Ahora incluimos **20 activos** del **S&P 500**, seleccionados por su relevancia en diferentes sectores:

- **Tecnología**: `AAPL`, `MSFT`, `GOOG`, `AMZN`, `NVDA`, `META`
- **Finanzas**: `BRK.B`, `V`, `PYPL`
- **Salud**: `JNJ`, `UNH`, `PFE`
- **Consumo**: `HD`, `DIS`
- **Energía**: `XOM`, `CVX`
- **Industria**: `BA`
- **Telecomunicaciones y Redes**: `CSCO`
- **Índice de referencia**: `SPY`

## 4. Modificación de Variables (Features)  
Se agregaron nuevas variables para mejorar la capacidad predictiva del modelo, incluyendo:  

- **Bandas de Bollinger**  
- **Indicadores técnicos adicionales**  

## 5. Ejecución del Backtesting  
Se probó el modelo con los cambios implementados para evaluar su rendimiento en el nuevo mercado y conjunto de activos.

