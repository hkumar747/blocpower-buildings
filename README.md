
#  BlocPower's building-level energy data


This repository hosts Jupyter notebooks that use BlocPower's massive building level energy data for 120+ million buildings, [hosted on EIDC Redivis](https://redivis.com/EIDC/datasets/c8kf-fwz3md6rs). They demonstrate how to perform several common operations, including data loading, aggregation to state/zipcode levels and visualization. They also discuss more advanced decision support frameworks, such as mathematical optimization for recommending energy policy interventions.

### [Notebook 1: Accelerating ETL with Polars and PySpark](https://github.com/hkumar747/blocpower-building-energy/blob/main/01_load_data.ipynb)

Notebook 1 loads and summarizes data by state, comparing the speed of Pandas, Polars and PySpark. 


### [Notebook 2: Energy retrofit optimization with Gurobi](https://github.com/hkumar747/blocpower-building-energy/blob/main/02_optimization_w_Gurobi.ipynb)

Notebook 2 shifts the focus towards optimization techniques, utilizing Gurobi to apply mixed integer programming (MIP) to select the most promising buildings for retrofitting given a fixed budget, for example, installing heat pumps.

![image](https://github.com/hkumar747/blocpower-buildings/assets/103491240/125cac77-4e16-4ea8-9e35-98cfd95b2a0b)

### [Notebook 3: User Guide](https://github.com/hkumar747/blocpower-building-energy/blob/main/03_Report_BlocPower.ipynb)

Code for the BlocPower User Guide, which compares the building data in this dataset to other ground-truth datasets for building counts and energy use.


### Getting Started

To explore the methodologies or replicate the analysis, just download and run the notebooks. It requires you to have API keys and authentication for the following:

- Gurobi (free for students)

- Redivis


