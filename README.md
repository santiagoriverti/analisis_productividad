# Análisis de la Productividad según el Uso de Redes Sociales

Este proyecto analiza cómo varía la productividad en diferentes sectores económicos en función del tiempo dedicado al uso de redes sociales. El código procesa datos de horas trabajadas, puestos de trabajo y valor añadido bruto (VAB) para calcular la productividad y estimar el impacto de las distracciones causadas por el uso de redes sociales.

## Descripción del Proyecto

El objetivo principal de este proyecto es cuantificar la merma en la productividad debido al uso de redes sociales en diferentes sectores económicos. Para ello, se clasifican los sectores en tres categorías según su nivel de productividad: **Baja**, **Media** y **Alta**. Luego, se ajustan las horas trabajadas en función de esta clasificación y se calcula la productividad antes y después de considerar las distracciones.

### Datos Utilizados
- **VAB_pb**: Valor Añadido Bruto por sector.
- **Puestos**: Número de puestos de trabajo por sector.
- **Horas**: Horas trabajadas por sector.

### Procesamiento
1. **Clasificación de Sectores**: Los sectores se clasifican en tres categorías según su productividad:
   - **Baja**: Sectores con menor productividad.
   - **Media**: Sectores con productividad intermedia.
   - **Alta**: Sectores con mayor productividad.
2. **Ajuste de Horas Trabajadas**: Se ajustan las horas trabajadas en función de la clasificación del sector, simulando el impacto del uso de redes sociales.
3. **Cálculo de Productividad**: Se calcula la productividad antes y después del ajuste, y se estima la merma en la productividad debido a las distracciones.

### Resultados
El código genera los siguientes resultados:
- **Productividad por Puestos**: Productividad calculada en función del número de puestos de trabajo.
- **Productividad por Horas**: Productividad calculada en función de las horas trabajadas.
- **Productividad con Distracciones**: Productividad ajustada considerando el impacto del uso de redes sociales.
- **Merma de Productividad**: Diferencia entre la productividad original y la productividad con distracciones.
- **Merma de Productividad en Valor**: Valor económico de la merma de productividad.
- **Merma de Productividad en Porcentaje**: Porcentaje de merma de productividad respecto al valor añadido bruto.

## Requisitos
Para ejecutar este proyecto, necesitas:
- Python 3.x
- Librerías de Python:
  - `pandas`
  - `numpy`
  - `openpyxl` (para manejar archivos de Excel)

Puedes instalar las dependencias con el siguiente comando:
```bash
pip install pandas numpy openpyxl
