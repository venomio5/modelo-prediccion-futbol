# **Soccer Forecasting Model**

## **Resumen**

Este proyecto construye un pipeline algorítmico de principio a fin para identificar cuotas mal valoradas (mispriced odds) en mercados de apuestas de fútbol con alta liquidez. En lugar de depender de la intuición o de análisis subjetivos, el objetivo fue desarrollar una ventaja (edge) medible y basada en datos, generando "líneas justas" (fair lines) calibradas y comparándolas contra los precios de las casas de apuestas en mercados como 1X2, Over/Under 2.5, Asian Handicap, entre otros.

## **Hallazgos Principales (Key Findings)**

* Las proyecciones pre-partido de xG del modelo logran un MAE de **0.847**, quedando a solo **0.061 goles** de la precisión del xG post-partido, a pesar de no tener acceso a datos reales de tiros.
* Las estimaciones de probabilidad están **mejor calibradas** que las cuotas del mercado, tanto en 1X2 (ECE 0.029 vs 0.039) como en Over/Under 2.5 (ECE 0.035 vs 0.039).
* Un backtest de 6 meses con más de 5,000 apuestas generó un **8.76% de ROI**, **$129K de ganancia** empezando con un bankroll de $10K, y un Sharpe ratio en el portafolio de **3.48**.
* Los mercados de Asian Handicap y Over/Under 2.5 fueron los más rentables, generando **más de $115K combinados**. El Correct Score produjo retornos negativos a pesar del alto volumen de apuestas.
* Un estudio de simulación (10,000 corridas aleatorias) confirma que los resultados no son producto del azar, obteniendo un **p-value de 0.0013**.

Para ver la historia completa, gráficos, la metodología de negocio y un desglose total del rendimiento → revisa la **[Página de Notion](https://www.notion.so/Advanced-Soccer-Forecasting-Model-322b7682d7a780b7a49ac85b794058a8)**.
