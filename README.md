# PTY-IQ — Sistema de Predicción de Vuelos ✈️

Sistema de inteligencia artificial para predecir retrasos de vuelos
en el Aeropuerto Internacional de Tocumen, Panamá.

## Estado actual
- ✅ Fase 1: Dataset histórico (525,370 vuelos reales — BTS)
- ✅ Fase 2: Modelo XGBoost — 92.9% de precisión
- ✅ Fase 3: Integración tiempo real (OpenSky Network API)
- ✅ Fase 4: Mapa interactivo de vuelos en tiempo real
- 🔄 Fase 5: Panel de control web (en progreso)

## Resultados del modelo
| Métrica | Valor |
|---|---|
| Precisión general | 92.9% |
| Vuelos de entrenamiento | 420,296 |
| Vuelos de prueba | 105,074 |
| Anticipación de alerta | 30–90 minutos |

## Tecnologías
Python · XGBoost · Pandas · Folium · Google Colab · OpenSky Network API

## Niveles de alerta
- 🟢 A tiempo — probabilidad < 30%
- 🟡 Riesgo leve — 30% a 50%
- 🟠 Riesgo moderado — 50% a 75%
- 🔴 Riesgo alto — más de 75%

## Contexto
Proyecto desarrollado para el ecosistema de aviación panameño,
con foco en Copa Airlines y el hub de conexiones de PTY.
