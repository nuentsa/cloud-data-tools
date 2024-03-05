# Cloud-Native platforms and  Data Pipelines to monitor your Daily Improvements
This repository provides some reference scripts and tutorials to access Cloud-native platforms for data  analytics and day-to-day productivity

* The [google-sheets-grafana](google-sheets-grafana/README.md) directory contains the source code for a Grafana dashboard, enabling you to monitor your daily exercise routines and other side  activities. 


    ![A Basic Pipeline with Google Sheets and Grafana](./google-sheets-grafana/Basic-Pipeline-Sheets-Grafana.png "A Basic Pipeline with Google Sheets and Grafana")


* The [runtastic_data](runtastic_data/Readme.md) directory provides a python notebook to  extract your workout files, cleans them up, and shows you some nice statistics so you can see how you're progressing over time. It loads the extracted data into a postgres database for further transformation and visualization with Grafana. A ready-to-use Grafana dashboard is provided in this same repository as well.


    ![A Data Pipeline to Analyze your Runtastic Data](./runtastic_data/Cloud_Data_Pipeline_for_fitness_data.png "A Data Pipeline to Analyze your Runtastic Data")
    ![Fitness Dashboard from Runtastic Data](././runtastic_data/Runtastic-Grafana-Dashboard.png "Fitness Dashboard from Runtastic Data")