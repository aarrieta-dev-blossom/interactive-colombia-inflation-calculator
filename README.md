# 💰 Calculadora Interactiva de Inflación Colombia

Herramienta web interactiva para calcular el impacto de la inflación en Colombia desde 2022 hasta 2026.

## 🌐 Demo en Vivo

**[Ver Calculadora](https://aarrieta-dev-blossom.github.io/interactive-colombia-inflation-calculator/)**

## ✨ Características

- 📊 **Cálculo en tiempo real** del valor ajustado por inflación
- 📅 **Selector de fechas** desde enero 2022 hasta diciembre 2025
- 💵 **Entrada personalizable** para cualquier monto en COP
- 📈 **Gráfica interactiva** mostrando la evolución del valor
- 📱 **Diseño responsive** para móviles y desktop

## 🎯 ¿Qué hace?

Calcula cuánto dinero necesitarías hoy para tener el mismo poder adquisitivo que una cantidad específica tenía en el pasado, considerando la inflación acumulada en Colombia.

**Ejemplo:** Si tenías $56 millones en enero 2022, necesitarías aproximadamente $76.8 millones en febrero 2026 para mantener el mismo poder de compra.

## 📊 Datos de Inflación

### Tasas Anuales
- **2022**: 13.12% (récord en 23 años)
- **2023**: 9.28%
- **2024**: 5.20%
- **2025**: 5.10%

### Factores Principales
- **2022**: Guerra en Ucrania, disrupciones post-pandemia
- **2023**: Política monetaria restrictiva
- **2024-2025**: Normalización gradual

## 📚 Fuentes de Datos

- [DANE](https://www.dane.gov.co) - Índice de Precios al Consumidor
- [Banco de la República](https://www.banrep.gov.co) - Reportes de Política Monetaria
- [BBVA Research](https://www.bbvaresearch.com) - Análisis económico
- [InflationTool.com](https://www.inflationtool.com/colombian-peso) - Datos históricos CPI

Ver [fuentes.md](fuentes.md) para referencias detalladas.

## 🚀 Uso Local

```bash
# Clonar el repositorio
git clone https://github.com/aarrieta-dev-blossom/interactive-colombia-inflation-calculator.git

# Abrir index.html en tu navegador
open index.html
```

## 📝 Metodología

**Fórmula de ajuste por inflación:**
```
Valor_ajustado = Valor_inicial × (CPI_final / CPI_inicial)
```

Donde CPI = Consumer Price Index (Índice de Precios al Consumidor)

## ⚠️ Disclaimer

Esta herramienta es informativa y educativa. Los cálculos se basan en datos oficiales públicos. Para decisiones financieras importantes, consulta con profesionales certificados.

---

**Última actualización**: Febrero 2026
