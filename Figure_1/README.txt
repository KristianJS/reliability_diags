README for idealised data

How to generate Figure 1: first run the RPC_contour_plot.ipynb and idealised_model_reliability_coefficient_contour_plot.ipynb notebooks, in any order. Then run the idealised_4_panel.ipynb notebook.


'RPC_contour_plot.ipynb' - notebook that generates RPC estimate values for each beta and signal/model noise ratios in contour plot of Figure 1. Output file: 'RPC_contour_data_est.txt'. This notebook also generates RPC value from formula in Siegert et. al. paper.

'idealised_model_reliability_coefficient_contour_plot.ipynb' - notebook that generates reliability regression coeffient computed from generated idealised model for each beta and signal/model noise ratios in contour plot of Figure 1. Output file: 'idealised_contour_data.txt'.

'idealised_4_panel.ipynb' - plots Figure 1 
panels (a) and (b) from output files 'idealised_contour_data.txt' and 'RPC_contour_data_est.txt'
panels (c) and (d) are two example relaibility diagrams for an overconfident and underconfident model.