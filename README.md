# Data Visualization of 3 Meteorological Events

<img src="thumbnails/thumbnail.png" alt="thumbnail" width="300"/>

_See the [Cookbook Contributor's Guide](https://projectpythia.org/cookbook-guide) for step-by-step instructions on how to create your new Cookbook and get it hosted on the [Pythia Cookbook Gallery](https://cookbooks.projectpythia.org)!_

This Project Pythia Cookbook examines three types of extreme weather events: tornado outbreaks, heatwaves, and lake-effect snowstorms to better understand their development and how accurately models and data can predict or visualize them. Using data from ERA5 reanalysis, GFS model outputs, satellite imagery, and radar, we analyze how each event evolved and how well key variables such as temperature, wind, and precipitation were represented. The case studies include the April 2011 tornado outbreak, the July 2023 U.S. heatwave and the November 2022 lake-effect snowstorm which together highlight different atmospheric processes across various spatial and temporal scales. By comparing model performance across these events, this study identifies both strengths and weaknesses in current forecasting systems and provides insight into how future prediction of extreme weather could be improved. 

(Jack Fordyce)

## Motivation

Extreme weather events such as tornado outbreaks, heatwaves, and lake-effect snowstorms represent some of the most significant challenges in meteorological forecasting and climate analysis. Each of these phenomena involves unique atmospheric dynamics, yet they are interconnected through shared physical processes and can be analyzed using similar datasets and modeling frameworks. This project aims to investigate these different types of extreme events using consistent data sources—such as ERA5 reanalysis, GFS model outputs, satellite observations, and station-based measurements—to better understand their evolution, predictability, and impacts.

By examining case studies of the April 2011 tornado outbreak, the July 2023 U.S. heatwave, and the November 2022 lake-effect snow event, we can compare how well models capture different forms of extreme weather. Through time series, spatial visualizations, and model verification analyses, the project will evaluate model skill across various variables (e.g., temperature, precipitation, and wind) and time scales. Ultimately, this comparative framework provides insight into both the strengths and limitations of current forecasting systems and highlights opportunities to improve prediction accuracy across multiple types of extreme events.

(Tianyu Zhu)

## Authors

[Sage Keidel](https://github.com/sagekeidel), [Tianyu Zhu](https://github.com/Tianyuzhu-9999), [Jack Fordyce](https://github.com/JackFwx124)

## Structure

This notebook will be composed of three main sections; ERA-5 Reanalysis, Radar and Satellite Imagery, and GFS Forecast Analysis.

### ERA-5 Reanalysis

The ERA5 Reanalysis example workflows will examine all three events (tornado outbreak, lake effect snowstorm, and heat wave) and the main 

### Radar and Satellite Imagery

The radar and satellite imagery workflows will again examine all three events using archived radar and satellite data, depending on what is more appropriate for understanding the event.

### GFS Forecast Analysis

The GFS Forecast Analysis workflows will examine how the all three events were handled by the GFS.

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter).

Note, not all Cookbook chapters are executable. If you do not see
the rocket ship icon, such as on this page, you are not viewing an
executable book chapter.


### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the `https://github.com/ProjectPythia/Meteorological_Data_Vis` repository:

   ```bash
    git clone https://github.com/ProjectPythia/Meteorological_Data_Vis.git
   ```

1. Move into the `Meteorological_Data_Vis` directory
   ```bash
   cd Meteorological_Data_Vis
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate Meteorological_Data_Vis
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
