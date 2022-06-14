# Code supporting "Relative sea level response to mixed carbonate-siliciclastic sediment loading along the Great Barrier Reef margin" by Lin et al. (Submitted)

This repository contains the Python code base for [Lin et al.]:  "Relative sea level response to mixed carbonate-siliciclastic sediment loading along the Great Barrier Reef margin".


**Project abstract:**

> The continental shelf along northeastern Australia is the world’s largest mixed carbonate-siliciclastic passive margin and the location of the Great Barrier Reef (GBR). Following sea-level transgression during the last deglaciation, extensive sediment was deposited along the GBR due to neritic carbonate deposition (including shelf edge reefs, Holocene reefs and Halimeda bioherms) and fluvial discharge of terrigenous siliciclastic sediments. Such sediment loading can alter local relative sea
level (RSL) by several metres through the sediment isostatic adjustment (SIA) process, a signal that is poorly constrained at the GBR. In this study, we used a glacial isostatic adjustment (GIA) model to develop an ensemble-based sediment loading history for the GBR since Marine Isotope Stage (MIS) 2. A Bayesian style framework is adopted to calibrate the sediment history ensemble and GIA model parameters using a sea-level database. According to our results, 1853.7 Gt (1613.1- 2078.7 Gt, 95% confidence interval) of sediment have been deposited across the GBR since MIS 2 (28 ka BP), causing spatially variable relative sea-level change with the highest magnitude (0.9-1.1 m) found in the outer shelf of the southern central GBR (18.4-21.6◦ S). Because the SIA-induced RSL rise is unrelated to ice mass loss, failing to correct for this signal will lead to systematic overestimation of grounded ice volume by up to ∼4.3 × 105 km3 during the Last Glacial Maximum. Additionally, we found that spatial variation in sediment loading and coastal environment may explain the different RSL history observed in published fossil coral reef records from Noggin Pass and Hydrographer’s Passage. These results highlight the importance of considering SIA for any postglacial sea-level studies adjacent to large sediment systems. Lastly, by quantifying both the GIA and SIA signals, we provide a spatially and temporally complete RSL reconstruction that is well-suited to be used as a boundary condition to study the evolution of the GBR shelf and slope sedimentary system.

If you have any questions, comments, or feedback on this work or code, please [contact Yucheng](mailto:yucheng.lin@durham.ac.uk)


## Getting Started

This codebase requires **Python version 3.5+** to run. It was written and tested with Python 3.5.2 and Jupyter Notebook 5.4.0.

### Dependencies

* [Pandas](https://pandas.pydata.org/) 1.0.1
* [NumPy](https://numpy.org/) 1.18.1
* [SciPy](https://www.scipy.org/) 1.4.1
* [Matplotlib](https://matplotlib.org/) 3.4.3
* [netCDF4](https://unidata.github.io/netcdf4-python/) 1.6.0
* [cartopy](https://pypi.org/project/Cartopy/) 0.18.0


## File Descriptions
* **GBR_Sediment.ipynb** - A notebook contains the code used for visualizing GBR relative sea level change and sediment deposition history
* **Data/GBR_RSL_2.nc** - A NetCDF file contains glacial isostatic and sediment isostatic adjustment caused relative sea level change field from MIS 2 to present
* **Data/CS_all.npy** - A npy file contains shoreline migration locations from MIS2 to present
* **Data/average_shelf_edge.npy** - A npy file contains ensemble mean shelf edge reef history.
* **Data/average_holocene.npy** - A npy file contains ensemble mean Holocene reef history.
* **Data/average_hali.npy** - A npy file contains ensemble mean *Halimeda* bioherms history.
* **Data/average_sili.npy** - A npy file contains ensemble mean siliciclastic sediment history.
* **Data/grid_co.npy** - A npy file contains sediment model grid cell locations.


## Corresponding Author

* **Yucheng Lin**

### Co-authors
* **Dr Pippa Whitehouse**
* **Dr Fiona Hibbert**
* **Dr Sarah Woodroffe**
* **Dr Gustavo Hinestrosa**
* **Prof. Jody M. Webster**

## License

This project is licensed under the MIT License - see the [LICENSE] file for details

## Acknowledgments

Y.L. was supported by China Scholarship Council - Durham University joint scholarship. F.D.H. received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie Sklodowska-Curie grant agreement (No. 838841 – ExTaSea). J.M.W received funding from the Australian Research Council (DP1094001). The authors acknowledge PALSEA, a working group of the International Union for Quaternary Sciences (INQUA) and Past Global Changes (PAGES), which in turn received support from the Swiss Academy of Sciences and the Chinese Academy of Sciences.

