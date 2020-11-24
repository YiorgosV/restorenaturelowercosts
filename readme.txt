Supplementary Data for the publication "Restoring nature at lower food production costs"

Contact: yiorgos.vittis@ouce.ox.ac.uk

This folder includes input data and R scripts to reproduce outputs for the estimation of global agricultural costs in the business-as-usual and the two land sparing scenarios.
Running the R script may require installation of additional libraries as indicated.

The default working directory is C:\. If run from a different folder, paths need to be edited in the R script "global_agricultural_crop_costs.r"


Script description:

global_agricultural_crop_costs.r     Estimation of costs for production of 10 major crops at global scales. 
                                     Includes the estimation of Intensification factor ratio, downscaling of costing information at sub-national scales
                                     and cost adjustments, calculation of costs by crop commodity and production scenario, assembling tables of total 
                                     costs at field and global scales.

                                    
Folders description:

Data
  Financial                           National-scale costs of production for the 10 considered crops, disaggregated in 8 distinct cost elements
  Geophysical
   Cropland extent                    Physical extent of crops in the business-as-usual and the two land sparing production scenarios
   Intensification Factor (IF) data   Physical information including current and attainable yields, N and P fertiliser application per crop, production 
                                      scenario and water regime incorporated for the estimation of input-output relationships (IF)
   Intensification Factor (IF) rates  Estimates of input-output relationships (IF)


Instructions:

The "global_agricultural_crop_costs.r" script needs to be run in an R environment, description of steps is provided in the script.

