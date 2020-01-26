<p align="center"><img src="https://github.com/gavin-bauer/earth-vital-signs/blob/master/assets/img/header.png"></p>

<p align="center">
  <img src="https://github.com/gavin-bauer/earth-vital-signs/blob/master/assets/img/demo.gif?raw=1" hspace="4">
  
</p>

<p align="center">
  <img alt="GitHub" src="https://img.shields.io/github/license/gavin-bauer/earth-vital-signs">

</p>

---

Based on data from NASA and NOAA, this project looks at the evolution of three of **Earth's Vital Signs** -- *Surface Temperatures*, *Arctic Sea Ice Concentrations*, *Carbon Dioxide Levels* -- indicating the rapid changes in global climate.

Part of the author's portfolio, Earth's Vital Signs is an end-to-end Data Science & Analytics project -- from ETL, data analysis & visualization to presenting the findings.

<br/>

## The project

#### ETL
Datasets were downloaded from [NASA](https://data.giss.nasa.gov/) and [NOAA](https://data.noaa.gov/dataset/), most often in .HDF, a format to store and organize large amounts of data. Data was extracted and transformed using the [netCDF4](https://pypi.org/project/netCDF4/) library.

#### Data analysis & visualization
Data analysis and visualization was performed using Python's [Numpy](https://numpy.org/), [Pandas](https://pandas.pydata.org/) and [Matplotlib](https://matplotlib.org/) libraries.

#### Presenting the findings
The findings were presented as a website on top of a template designed by [Creative Tim](https://www.creative-tim.com/) and hosted on [Render](https://render.com/).

<br/>

## Installation

#### Downloading & editing the website

1. Clone the repository with the 'clone' command, or just download the zip.
```
$ git clone git@github.com:https://github.com/gavin-bauer/earth-vital-signs.git
```
2. Download or Open your IDE (i.e. [Atom](https://atom.io/)) and start editing.

#### Running notebooks
Jupyter notebooks are available for testing and reproducing analyses and visualizations in this [folder](https://github.com/gavin-bauer/earth-vital-signs/tree/master/notebooks) and can be run directly in [Google Colaboratory](https://colab.research.google.com/).

#### Deployment

1. Sign up for a [Render](https://render.com/) account.
2. Create a new Web Service on Render and grant Render permission to access the GitHub repository containing the project.
3. On the deployment screen, pick a name for the website.
4. Click Save Web Service. The website will begin building and should be live in a few minutes at the URL displayed in the Render dashboard.

<br/>

## Built with

* [Python](https://www.python.org/) - Programming language
* [Numpy](https://numpy.org/), [Pandas](https://pandas.pydata.org/) & [Matplotlib](https://matplotlib.org/) - Data centric Python packages 
* [Atom](https://atom.io/) - Text editor
* [Google Colaboratory](https://colab.research.google.com/) - Run Jupyter Notebooks in the cloud
* [Render](https://render.com/) - Cloud platform to host static websites 

## Author

* **Gavin Bauer** - Data Analyst of 5+ years experience | Current: 🦉[@KeringGroup](https://www.kering.com/) | Past: ⚡[@Total](https://www.total.com/en), 🌱[@YvesRocherFR](https://groupe-rocher.com/en)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

## Acknowledgements
* [NASA](https://data.giss.nasa.gov/) & [NOAA](https://data.noaa.gov/dataset/) for providing the datasets
* [Creative Tim](https://www.creative-tim.com/) for providing the website template
