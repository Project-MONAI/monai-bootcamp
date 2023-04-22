# MONAI Bootcamp
This repository hosts the notebooks for hosting a MONAI Bootcamp event. The data required for the notebooks are available through the download mechanisms given in each notebook or through the organizers.

You can find videos for our 2021 MONAI Bootcamp on the [MONAI YouTube Channel](https://www.youtube.com/playlist?list=PLtoSVSQ2XzyCobzE6NvwjNpITsQyPUtfs). It partially covers some of the material below and shows how we ran the event.

Most of the notebooks in this repository would benefit considerably from having GPU support enabled. Therefore, it is recommended to run notebooks on Google Colab.

### MONAI Core:
**Intro to MONAI Core**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Project-MONAI/monai-bootcamp/blob/main/MONAICore/Intro%20to%20MONAI.ipynb)

[![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github.com/Project-MONAI/monai-bootcamp/blob/main/MONAICore/Intro%20to%20MONAI.ipynb) (Requires Referral Code)

**MONAI End-to-End Workflow**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Project-MONAI/monai-bootcamp/blob/main/MONAICore/MONAI%20End-to-End%20Workflow.ipynb)

[![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github.com/Project-MONAI/monai-bootcamp/blob/main/MONAICore/MONAI%20End-to-End%20Workflow.ipynb) (Requires Referral Code)

**MONAI Bundles and Model Zoo**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Project-MONAI/monai-bootcamp/blob/main/MONAICore/MONAI%20Bundle%20and%20MONAI%20Model%20Zoo.ipynb)

[![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github.com/Project-MONAI/monai-bootcamp/blob/main/MONAICore/MONAI%20Bundle%20and%20MONAI%20Model%20Zoo.ipynb) (Requires Referral Code)

### MONAI Deploy:
**(Optional)Creating a Simple Image Processing App with MONAI Deploy App SDK**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Project-MONAI/monai-bootcamp/blob/main/MONAIDeploy/00_basic_operators.ipynb)

**(Optional) Deploying a MedNIST Classifier App with MONAI Deploy App SDK**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Project-MONAI/monai-bootcamp/blob/main/MONAIDeploy/00_mednist_app.ipynb)

**Creating a Segmentation App with MONAI Deploy App SDK**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Project-MONAI/monai-bootcamp/blob/main/MONAIDeploy/01_segmentation_app.ipynb)

**Bring Your Own Model with MONAI Deploy App SDK**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Project-MONAI/monai-bootcamp/blob/main/MONAIDeploy/02_byom_app.ipynb)

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
