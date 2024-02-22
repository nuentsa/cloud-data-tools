# Explore your Runtastic (Adidas Running) Data with a Jupyter Notebook on Google Cloud

This notebook  extracts your workout files, cleans them up, and shows you some cool graphs so you can see how you're progressing over time. oads the extracted into a postgres database for further transformation and visualization with Grafana.

## How to use:

1. Get the Notebook:

* GitHub Users:
    * If you have a GitHub account, simply clone this repository.
* Non-GitHub Users:
    * Download the notebook directly.
2. Open in Google Colab:
* Navigate to [Google Colab](https://colab.research.google.com/).
* GitHub Users:
    * Set up access to your GitHub account and the cloned repository.
* Non-GitHub Users:
    * Upload the downloaded notebook.
4. Manage Secrets:
* Go to the Secrets section in Colab.
* Create/configure the following secrets:
    * Google Drive ID (optional):
        * Enter the ID of your Runtastic ZIP file if you want to download it from Google Drive.
        * You can leave this blank to upload the file manually (see step 5).
    * Postgres Connection String (optional):
        * If you want to upload data to a Postgres database, provide your connection string here.
        * You can skip this if you don't need database integration.
5. Run the Notebook:
    * Click the "Run" button or press Shift+Enter in each code cell.
6. Google Drive Access (Optional):
    * If you entered a Google Drive ID, the notebook will request permission to access your drive.
    * Grant access to download the Runtastic ZIP file.
7. Manual File Upload (Optional):
    * If you didn't use Google Drive, update the relevant code cell to specify the local path of your Runtastic ZIP file.
8. Explore and Adapt:
    * You're now ready to explore your Runtastic data!
    * Feel free to adjust the code to suit your specific needs and analysis goals.

## Resources

* [Google Colab](https://colab.research.google.com/)
* [Jupyter Documentation](https://docs.jupyter.org/en/latest/)

## Contributing

We welcome contributions to this repository. If you would like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.