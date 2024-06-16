# Final-project

## Summary
This project aims to analyze the impact of different age population groups on GDP growth and validate the convergence hypothesis using econometric methods. Additionally, I explore the use of birth rate as an instrumental variable in a two-stage least squares (2SLS) regression.

## Methods

### Convergence Hypothesis
First, I validate the convergence hypothesis by examining the relationship between initial GDP per capita and subsequent GDP per capita growth rates across different countries. The hypothesis suggests that poorer countries tend to grow faster than richer ones, leading to a convergence in GDP per capita over time.

### Age Structure and GDP Growth
Next, I analyze the impact of different age population groups (Population 0-14, Population 15-64, Population 65+) on GDP growth. I utilize OLS regression to estimate these effects.

### Instrumental Variable Analysis
To address potential endogeneity issues, I use the birth rate as an instrumental variable in a two-stage least squares (2SLS) regression. 

## Results
- **Convergence Hypothesis**: The analysis provides evidence supporting the convergence hypothesis, with poorer countries exhibiting higher growth rates compared to richer countries.
- **OLS Regression**: The OLS regression results indicate significant effects of different age population groups on GDP growth. Specifically, the population aged 0-14 and 65+ have significant impacts on GDP growth.
- **2SLS Regression**: The 2SLS regression results, using birth rate as an instrumental variable, were not satisfactory. The regression outputs indicate issues such as weak instruments and potentially insufficient sample size, leading to unreliable estimates.

## Files
- `Final_project.ipynb`: The Jupyter Notebook containing the empirical analysis.
- `finaldata.xlsx`: The dataset used for the analysis.

## Conclusion
The results show significant relationships between age structure and GDP growth. However, the 2SLS regression results suggest the need for further refinement. Potential improvements include increasing the sample size and selecting stronger instrumental variables to obtain more reliable estimates.

## Future Improvements
- **Increase Sample Size**: Collect more data to enhance the robustness of the regression estimates.
- **Improve Instrumental Variables**: Identify and use stronger instrumental variables to address endogeneity issues more effectively.
- **Refine Model Specification**: Consider additional control variables and interaction terms to better capture the complex dynamics between age structure and GDP growth.

