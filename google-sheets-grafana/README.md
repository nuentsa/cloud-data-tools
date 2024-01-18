# Grafana Dashboard for Tracking Exercise Routines and Side Activities

This repository contains the source code for a Grafana dashboard that can be used to track your daily exercise routines and other side activities.

## Getting Started
The dashboard and required Google sheet data source is best described in this article [medium article](https://medium.com/@Dee.N/turn-your-daily-tasks-into-actionable-insights-a-guide-to-creating-a-simple-and-no-code-dashboard-2696b67087c8))

## Dashboard Overview

The dashboard consists of several panels :

* **Exercise Progress:** This panel shows your average exercise duration, number of exercise sessions, overall exercise time...
* **Side Activity Time Distribution:** This panel shows the total time spent on various side activities.
* **Recent Side Activities:** This panel shows a detailed breakdown of your recent side activities, including duration, date, and personal notes.


## Data Source

The dashboard uses Google Sheets as the data source. The sheet referenced in the dashboard is available [here](https://docs.google.com/spreadsheets/d/1wy9196yvqQ0G1I6V7H69bhdJYQOZXKd9lTvS8ILy0wU/edit#gid=0), which you can duplicate for your own purposes. 
In Grafana, you will need to create a new Google Sheet data source and provide your Google API Key. All required steps are described in the referenced article.

## Resources

* [Grafana official website](https://grafana.com/)
* [Grafana documentation](https://grafana.com/docs/)

## Contributing

We welcome contributions to this repository. If you would like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
