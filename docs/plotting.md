# Plotting in Pandas: Eine Kurze Einführung

Pandas bietet leistungsstarke Funktionen zur Visualisierung von Daten, indem es auf die Matplotlib-Bibliothek zugreift. Mit der `.plot()`-Methode können Daten einfach in verschiedene Diagrammtypen umgewandelt werden.

## Grundlegende Nutzung

Die `DataFrame.plot()`- und `Series.plot()`-Methoden ermöglichen schnelle Visualisierungen:

```python
import pandas as pd
import matplotlib.pyplot as plt

# Beispiel-Daten
df = pd.DataFrame({
    'Jahr': [2020, 2021, 2022, 2023, 2024],
    'Umsatz': [100, 150, 200, 250, 300]
})

# Linienplot
df.plot(x='Jahr', y='Umsatz', kind='line', marker='o', title='Umsatzentwicklung')
plt.show()
```

## Diagrammtypen

Pandas unterstützt verschiedene Diagrammtypen durch den `kind`-Parameter:

- **'line'** – Linienplot (Standard)
- **'bar'** – Säulendiagramm
- **'barh'** – Horizontalbalkendiagramm
- **'hist'** – Histogramm
- **'box'** – Boxplot
- **'scatter'** – Scatterplot (`x` und `y` müssen explizit angegeben werden)
- **'pie'** – Kreisdiagramm (nur für `Series` sinnvoll)

```python
# Balkendiagramm
df.plot(kind='bar', x='Jahr', y='Umsatz', title='Umsatzvergleich')
plt.show()
```

## Anpassung der Plots

- **Farben & Stile**: Über `color` und `style` anpassbar
- **Achsentitel & Legenden**: Über `xlabel`, `ylabel` und `legend()`
- **Größe & Layout**: `figsize=(width, height)`

```python
df.plot(kind='scatter', x='Jahr', y='Umsatz', color='red', title='Streudiagramm')
plt.xlabel('Jahr')
plt.ylabel('Umsatz')
plt.grid(True)
plt.show()
```

## Zusammenfassung

Pandas macht das Plotten einfach und intuitiv, insbesondere für schnelle Datenanalysen. Fortgeschrittene Anpassungen können durch direkte Matplotlib-Nutzung erfolgen.
