# Google AI Notebooks (The Frontend)

This README contains instructions on how to use Google [AI Notebooks](https://cloud.google.com/ai-platform-notebooks).

## Launch AI Platform Notebooks 

Click on the Navigation Menu and navigate to AI Platform, then to Notebooks.

[![Open AI Notebooks][notebook_img]][notebook_link]

[notebook_img]: https://cdn.qwiklabs.com/fnUEPKKDGG4Xw1nbWJRpVfg02LTmJLOrel2Ny42JQVk%3D
[notebook_link]: https://console.cloud.google.com/ai-platform/notebooks/list

## Setup (Done for you already)
**We have done this for you, so feel free to just read through it**

Enable the Notebooks API:

    gcloud services enable notebooks.googleapis.com

On the Notebook instances page, click New Instance. Select the Python 3 version. 
For these demo notebooks, the default configuration should do the trick.

This creates a Jupyter Notebook instance (which, behing the scenes, is actually just running on Google Compute Engine). 


## Open the Notebook Instance
Once the notebook has been provisioned, click 'Open JupyterLab'. A JupyterLab window will open in a new tab. 

[![Open Jupyter Notebooks][jupyter_img]][jupyter_link]

[jupyter_img]: https://cdn.qwiklabs.com/fowDLNZLw1WB1zkF9BBSwzNvjBnZyducp45ui%2FBkXTg%3D
[jupyter_link]: https://console.cloud.google.com/ai-platform/notebooks/list


## Getting the sample code

Enable the [Cloud Source Repositories API](https://console.cloud.google.com/flows/enableapi?apiid=sourcerepo.googleapis.com&redirect=https://cloud.google.com/source-repositories/docs/quickstart&_ga=2.183937445.2048159139.1643037343-1135681951.1638371582)

In the JupyterLab window that opens, click 'Git' in the top menu and clone the repository (replace with your clone/fork):

    https://github.com/Jiaxen/sample-gcp-nlp-flask.git

You should see the repo cloned into the navigator on the left side of the page. Navigate into the sample notebooks:

    sample-gcp-nlp-flask/frontend_notebook
    
You can now read through the notebook and the sample outputs.

## Analysing Articles

Develop your text anlaysis solution. You can find articles to analyse in the /articles directory.


