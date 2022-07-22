# MONAI Bootcamp
This repository hosts the notebooks for hosting a MONAI Bootcamp event. The data required for the notebooks are available through the download mechanisms given in each notebook or through the organizers.

You can find videos for our 2021 MONAI Bootcamp on the [MONAI YouTube Channel](https://www.youtube.com/playlist?list=PLtoSVSQ2XzyCobzE6NvwjNpITsQyPUtfs). It partially covers some of the material below and shows how we ran the event.

Most of the notebooks in this repository would benefit considerably from having GPU support enabled. Therefore, it is recommended to run notebooks on Google Colab.

## Run on Google Colab (Recommended)

Developers can access the notebooks in Google Colab by using the links below:

**Enabling GPU Support in Google Colab**

To use GPU resources through Google Colab, remember to change the runtime to GPU:

1. From the "Runtime" menu, select "Change Runtime Type"
2. Choose "GPU" from the drop-down menu
3. Click "Save"

Running

```shell
!nvidia-smi
```

in a cell will verify this has worked and show you what kind of hardware you have access to.

### MONAI Core:
* <a target="_blank" href="https://colab.research.google.com/github/zephyrie/monai-bootcamp/blob/main/MONAICore/1. Getting Started with MONAI.ipynb">1. Getting Started with MONAI Core</a>
* <a target="_blank" href="https://colab.research.google.com/github/zephyrie/monai-bootcamp/blob/main/MONAICore/2. MONAI Datasets and Caching.ipynb">2. MONAI Datasets and Caching with MONAI Core</a>
* <a target="_blank" href="https://colab.research.google.com/github/zephyrie/monai-bootcamp/blob/main/MONAICore/3. End-To-End Workflow with MONAI.ipynb">3. End-To-End Workflow with MONAI Core</a>

### MONAI Deploy:
* <a target="_blank" href="https://colab.research.google.com/github/zephyrie/monai-bootcamp/blob/main/MONAIDeploy/01_simple_app.ipynb">1. Creating a Simple Image Processing App with MONAI Deploy App SDK</a>
* <a target="_blank" href="https://colab.research.google.com/github/zephyrie/monai-bootcamp/blob/main/MONAIDeploy/02_mednist_app-prebuilt.ipynb">2. Deploying a MedNIST Classifier App with MONAI Deploy App SDK</a>
* <a target="_blank" href="https://colab.research.google.com/github/zephyrie/monai-bootcamp/blob/main/MONAIDeploy/03_segmentation_app.ipynb">3. Creating a Segmentation App with MONAI Deploy App SDK</a>

While using Google Colab, you cannot fully utilize Docker for packaging your MONAI Deploy Application Package (MAP). For this reason, we've commented out the docker-specific instructions within the notebooks so that there are no issues. These can be uncommented and run to demonstrate the packaging process if running locally.

### MONAI Label:
MONAI Label requires a running server and an external viewing application, so we can't easily host a hands-on example using Google Colab.  If you're interested in setting things up for MONAI Label locally, you can find the installation instructions in the installation section below. 

You can find a video presentation + demo walkthrough by Andres Diaz-Pinto at the 2021 MONAI Bootcamp on YouTube here: https://www.youtube.com/watch?v=o8HipCgSZIw&list=PLtoSVSQ2XzyCobzE6NvwjNpITsQyPUtfs

## Install a Local Environment

To set up your local environment, you'll need to follow MONAI Core, MONAI Label, and MONAI Deploy installation instructions. Below you can find links to each projects installation documentation:

* [MONAI Core Installation](https://docs.monai.io/en/stable/installation.html)
* [MONAI Label Installation](https://docs.monai.io/projects/label/en/latest/installation.html)
* [MONAI Deploy Installation](https://docs.monai.io/projects/monai-deploy-app-sdk/en/latest/getting_started/installing_app_sdk.html)

If your local machine has GPU support, please follow the official [PyTorch documentation](https://pytorch.org/get-started/locally/) on how to install PyTorch with GPU support in your local environment, depending on your system configuration.