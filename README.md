## Data in Brief ~ Repository
This repository, together with the [Forest-fires-GHG database](https://data.mendeley.com/datasets/v7gxtvv9z3/draft?a=b85f3cc2-168b-45d2-8f00-ed874a9e2d5c), supplement the following publication: *Ribeiro-Kumara, C., et al., 2020. How do forest fires affect soil greenhouse gas emissions in upland boreal forests? A review. Environmental Research.* [184.10.1016/j.envres.2020.109328](https://doi.org/10.1016/j.envres.2020.109328).

The current repository includes the scripts used to filter outliers and to generate the graphs used to aid visualization and identification of trends of the expected value of the distribution of carbon dioxide (CO<sub>2</sub>), methane (CH<sub>4</sub>) and nitrous oxide (N<sub>2</sub>O) mean fluxes over time. **For reproducible R scripts, please check this** [notebook](https://c-riku.github.io/datainbrief-binder/).

## Instructions on how to use the scripts in this repository
- Figure 1
   - Load file *ghg-fluxes.jmp* (from the dataset available in *Mendeley Data*) into JMP
   - Run script *outliers-Ra-Rh.jsl* to screen for outliers
   - Decide whether to remove outliers or not (in the review article we chose not to)
   - Run script *figure-1.jsl*
