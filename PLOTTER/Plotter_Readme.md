## DataFrame Plotter 📊📈

This Python script allows you to quickly visualize your DataFrame using interactive plots. It utilizes the `pandas`, `numpy`, and `cufflinks` libraries for data manipulation and plotting, and `plotly` for interactive visualization.

### Libraries Used
- **pandas** 🐼: For data manipulation and analysis.
- **numpy** 🔢: For numerical operations.
- **chart_studio.plotly** 📊: For interactive plots.
- **plotly.offline** 📊: For offline plotting.
- **cufflinks** 📊: To connect plotly with pandas.

### Functions and Methods
- **createdata(data)** 🔄: Creates a DataFrame based on user input (random data, custom data, or uploaded file).
- **plotter(plot)** 📊: Plots the entire DataFrame based on the selected plot type.
- **plotter2(plot)** 📊: Plots specific columns of the DataFrame based on the selected plot type.
- **main(cat)** 🔄: Main function to select the type of data to plot and the plot type.

### How to Use
1. Run the script.
2. Select the type of data you want to plot (random data, custom data, or uploaded file).
3. If custom data is selected, enter column names and values.
4. Select whether to plot all columns or specific columns.
5. Select the type of plot you want to generate.

### Note
- Ensure you have the required libraries installed (`pip install pandas numpy cufflinks chart_studio plotly`).
- This script provides a quick and interactive way to visualize your DataFrame, ideal for exploratory data analysis.
