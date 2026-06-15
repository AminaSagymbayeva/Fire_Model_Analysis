# Tool for Streamlining Fire Model Simulation Assessment
This repository is the result of my internship at Columbia Climate School Center for Climate Systems Research (October 2026 - May 2026) under the guidance of Dr Keren Mezuman. 
This tool was created for the analysis of ensemble simulations produced by PyrE, an interactive fire module within the NASA GISS Earth System Model (Mezuman et al., 2020). The tool provides visualizations as well as statistical parameters for the input data to assess the model performace against observed burned area for a given period of time (Chen et al., 2023). The tool is currently applied for the analysis of burned area globally and within the US territory but it can be easily applied to other regions provided that relevant masks are available. The tool assess the model performance from three perspectives:
1. BA distribution skill: histograms, log-transformed, zero-excluded Perkin’s skill score (Perkins et al., 2007), AEP curve, Wilcoxon rank sum test, and rank-biserial correlation; 
2. Spatial skill: spatial Spearman’s rho, mean seasonal BA difference;
3. Temporal skill: time series reconstruction, seasonal averages.

We appreciate your feedback and contrubution!

**References:**
*  Chen, Y., Hall, J., Dave van Wees, Niels Andela, Stijn Hantson, Giglio, L., van, Morton, D. C., & Randerson, J. T. (2023). Multi-decadal trends and variability in burned area from the fifth version of the Global Fire Emissions Database (GFED5). Earth System Science Data, 15(11), 5227–5259. https://doi.org/10.5194/essd-15-5227-2023
*  Mezuman, K., Kostas Tsigaridis, Faluvegi, G., & Bauer, S. E. (2020). The interactive global fire module pyrE (v1.0). Geoscientific Model Development, 13(7), 3091–3118. https://doi.org/10.5194/gmd-13-3091-2020
*  Perkins, S. E., Pitman, A. J., Holbrook, N. J., & McAneney, J. (2007). Evaluation of the AR4 Climate Models’ Simulated Daily Maximum Temperature, Minimum Temperature, and Precipitation over Australia Using Probability Density Functions. Journal of Climate, 20(17), 4356-4376. https://doi.org/10.1175/JCLI4253.1





