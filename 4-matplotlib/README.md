# Matplotlib Tutorials

This directory contains comprehensive tutorials and examples for Matplotlib, a powerful plotting and visualization library for Python.

## What is Matplotlib?

Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. It provides:
- Publication-quality figures in various formats
- A wide variety of plot types
- Extensive customization options
- Integration with NumPy and Pandas
- Support for multiple backends

## Why Use Matplotlib?

Matplotlib is essential for data visualization because it:
- Provides complete control over plot appearance
- Supports a wide range of plot types
- Integrates seamlessly with NumPy and Pandas
- Allows saving figures in multiple formats
- Offers extensive customization for professional presentations

## Directory Structure

The tutorials are organized into numbered directories covering specific topics:

### Core Concepts
- **1_intro/**: Introduction to Matplotlib and basic plotting
- **2_format_strings/**: Format strings for line styles, colors, and markers
- **3_legends_grid_axes_labels/**: Adding legends, grids, and axis labels

### Chart Types
- **4_bar_chart/**: Creating bar charts
- **5_histogram/**: Creating histograms
- **6_pie_chart/**: Creating pie charts

### Advanced Features
- **10_subplots.ipynb**: Creating subplots and multiple plots
- **7_save_chart/**: Saving charts to files in various formats

## Getting Started

### Prerequisites

Install Matplotlib:

```bash
pip install matplotlib
```

For better integration with Jupyter Notebooks:
```bash
pip install matplotlib ipykernel
```

### Running the Tutorials

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open the notebooks in numerical order for a structured learning path

3. Run each cell to see the visualizations

## Key Topics Covered

### Introduction to Matplotlib
- Basic plotting with pyplot
- Creating simple line plots
- Understanding the Matplotlib architecture
- Figure and axes objects

### Format Strings
- Line styles (solid, dashed, dotted, dashdot)
- Colors (named colors, hex codes, RGB)
- Markers (circles, squares, triangles, etc.)
- Combining format options

### Customization
- Adding legends
- Configuring grids
- Setting axis labels and titles
- Customizing tick marks and labels
- Adjusting figure size and layout

### Bar Charts
- Creating vertical and horizontal bar charts
- Grouped bar charts
- Stacked bar charts
- Customizing bar appearance

### Histograms
- Creating histograms
- Adjusting bins
- Normalizing histograms
- Multiple histograms on the same plot

### Pie Charts
- Creating pie charts
- Customizing slices
- Adding labels and percentages
- Exploding slices
- Styling pie charts

### Subplots
- Creating multiple subplots
- Arranging subplots in grids
- Sharing axes between subplots
- Adjusting spacing and layout

### Saving Charts
- Saving figures to files
- Supported file formats (PNG, PDF, SVG, etc.)
- Setting resolution (DPI)
- Saving with different backends

## Common Plot Types

While this tutorial covers the basics, Matplotlib supports many more plot types:
- Line plots
- Scatter plots
- Bar charts
- Histograms
- Pie charts
- Box plots
- Violin plots
- Heatmaps
- Contour plots
- 3D plots
- And many more

## Best Practices

1. **Import Convention**: Import Matplotlib's pyplot module:
   ```python
   import matplotlib.pyplot as plt
   ```

2. **Use Object-Oriented API**: For more control, use the object-oriented API:
   ```python
   fig, ax = plt.subplots()
   ax.plot(x, y)
   ```

3. **Set Figure Size Early**: Define figure size when creating plots:
   ```python
   plt.figure(figsize=(10, 6))
   ```

4. **Add Labels and Titles**: Always include axis labels, titles, and legends for clarity

5. **Save High-Resolution Figures**: Use appropriate DPI when saving:
   ```python
   plt.savefig('plot.png', dpi=300)
   ```

6. **Close Figures**: Close figures to free memory, especially in loops:
   ```python
   plt.close()
   ```

## Integration with NumPy and Pandas

Matplotlib works seamlessly with NumPy arrays and Pandas DataFrames:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

# With NumPy
x = np.linspace(0, 10, 100)
y = np.sin(x)
plt.plot(x, y)

# With Pandas
df = pd.read_csv('data.csv')
df.plot(x='column1', y='column2', kind='bar')
```

## File Formats

Matplotlib can save figures in various formats:
- PNG (raster, good for web)
- PDF (vector, good for documents)
- SVG (vector, good for web)
- EPS (vector, good for publications)
- JPG/JPEG (raster, compressed)

## Additional Resources

- [Matplotlib Official Documentation](https://matplotlib.org/stable/contents.html)
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index.html)
- [Matplotlib Gallery](https://matplotlib.org/stable/gallery/index.html)
- [Matplotlib API Reference](https://matplotlib.org/stable/api/index.html)

## Example Workflow

1. Import necessary libraries
2. Prepare your data (using NumPy or Pandas)
3. Create a figure and axes
4. Plot your data
5. Customize the plot (labels, legends, colors)
6. Save or display the figure

## Next Steps

After completing these tutorials, you'll be able to:
- Create professional-quality visualizations
- Customize plots for presentations and publications
- Integrate plotting into your data analysis workflow
- Combine Matplotlib with NumPy and Pandas for complete data science solutions

Consider exploring additional visualization libraries like Seaborn (built on Matplotlib) for statistical visualizations, or Plotly for interactive plots.

