# 🏦 Algorithmic Trading & Macro-Risk Analysis

## 📋 Resumen Ejecutivo
Este proyecto integra **Teoría Económica**, **Ciencia de Datos** y **Machine Learning** para analizar la viabilidad de inversión en activos tecnológicos (Tesla) bajo diferentes regímenes de política monetaria.

A diferencia de los análisis técnicos tradicionales, este modelo cruza variables macroeconómicas reales (Tasas de la Reserva Federal) con modelos predictivos de Inteligencia Artificial para estimar retornos ajustados al riesgo.

## 🛠️ Stack Tecnológico
* **Python:** Pandas, NumPy, Matplotlib, Seaborn.
* **APIs Financieras:** Yahoo Finance (`yfinance`), Reserva Federal (`pandas-datareader`).
* **Machine Learning:** Facebook Prophet (Series de Tiempo), Scikit-Learn (Regresión Lineal).
* **Modelado Financiero:** Optimización de Markowitz (Frontera Eficiente), CAPM, Value at Risk (VaR).

## 📊 Hallazgos Clave

### 1. Impacto Macroeconomico (Fed Rates vs Equity)
Se demostró una correlación inversa significativa entre la Tasa del Tesoro a 10 años (DGS10) y la valoración de activos de crecimiento. El ciclo de alza de tasas de 2022 explicó matemáticamente la contracción en el precio de Tesla, validando la teoría de flujo de caja descontado.

### 2. Perfil de Riesgo (CAPM & VaR)
* **Beta Calculada:** 2.28 (El activo es hipersensible a movimientos del mercado).
* **Value at Risk (VaR 99%):** -10.94%. El modelo estima que en escenarios de estrés extremo (Cisne Negro), la pérdida diaria máxima esperada supera el 10%, lo que sugiere la necesidad de coberturas (hedging) activas.

### 3. Proyecciones con IA (Prophet)
El modelo de Facebook Prophet proyecta una tendencia alcista estructural para el ciclo 2025-2026, aunque con un ensanchamiento en los intervalos de confianza, indicando mayor volatilidad futura.

---
*Desarrollado por axel giraldo - Economista & Data Scientist*
