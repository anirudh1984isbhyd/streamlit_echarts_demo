# Integrating E-Charts with Streamlit for data visualisations

## Installation and setup

Please ensure you have [streamlit](https://www.streamlit.io/) and Python <=3.8.x installed. If you have python 3.9.x, create and use a conda environment as follows

``` bash
conda create --name echarts_streamlit python=3.8
conda activate echarts_streamlit
```

Use the following command to deactivate
``` bash
conda deactivate
```

To install the python requirements, run

``` bash
pip install -r requirements.txt
```

And finally run the app with

``` bash
streamlit run app.py
```

and you can view the app at localhost:8501


## Background

The app contains examples and the plotted data for different types of charts available, for example line chart, pie chart, heatmaps, etc. along with an example named as "click event" to demonstrate the click event in echarts.

The above mentioned features have been implemented using a streamlit component [streamlit-echarts](https://discuss.streamlit.io/t/streamlit-echarts-early-build/3655) available [here](https://github.com/andfanilo/streamlit-echarts)
