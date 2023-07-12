# MONAI Bootcamp Repository

Welcome to the MONAI Bootcamp repository! This repository contains notebooks for hosting a MONAI Bootcamp event. The notebooks provide valuable resources for learning and exploring the MONAI framework.

#### Video Resources
We have recorded video sessions for our previous bootcamps, including the [2021 MONAI Bootcamp](https://www.youtube.com/playlist?list=PLtoSVSQ2XzyCobzE6NvwjNpITsQyPUtfs) and the [2023 MONAI Bootcamp](https://www.youtube.com/playlist?list=PLtoSVSQ2XzyAJAGzaHF0nUIkav0BnxhrJ). These videos are available on the [MONAI YouTube Channel](https://www.youtube.com/c/Project-MONAI). They provide in-depth explanations and demonstrations of the concepts covered in the bootcamp.

#### GPU Support 
To get the most out of the notebooks, we strongly recommend running them with GPU support enabled. You can easily run the notebooks on Google Colab or Amazon SageMaker Studio Lab, which provides access to GPUs. Using GPUs significantly accelerates the computation and improves the performance of MONAI.

Feel free to explore the notebooks and video resources to enhance your understanding of MONAI. Happy learning!

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

While using Google Colab or Studio Lab, Docker cannot be fully utilized for packaging your MONAI Deploy Application Package (MAP). To avoid any issues, we have commented out the docker-specific instructions in the notebooks. If you run the notebooks locally, you can uncomment and execute these instructions to demonstrate the packaging process.

### MONAI Label:
Running MONAI Label requires a dedicated server and an external viewing application, which makes it challenging to provide a hands-on example using Google Colab or Amazon SageMaker Studio Lab. However, if you're interested in exploring MONAI Label, you can follow the installation instructions provided in the section below to set it up locally.

For a video presentation and demo walkthrough by Andres Diaz-Pinto at the 2021 MONAI Bootcamp, visit this [MONAI YouTube Channel](https://www.youtube.com/watch?v=o8HipCgSZIw&list=PLtoSVSQ2XzyCobzE6NvwjNpITsQyPUtfs).

Follow the installation instructions and watch the video to learn more about MONAI Label and its usage for your projects.

## Install a Local Environment

To set up your local environment, please follow the installation instructions for MONAI Core, MONAI Label, and MONAI Deploy. Below are the links to the installation documentation for each project:

* [MONAI Core Installation](https://docs.monai.io/en/stable/installation.html)
* [MONAI Label Installation](https://docs.monai.io/projects/label/en/latest/installation.html)
* [MONAI Deploy Installation](https://docs.monai.io/projects/monai-deploy-app-sdk/en/latest/getting_started/installing_app_sdk.html)

If your local machine supports GPU, refer to the official [PyTorch documentation](https://pytorch.org/get-started/locally/) for instructions on installing PyTorch with GPU support based on your system configuration.

## Additional Resources

### AWS
AWS has been actively involved in sponsoring and presenting at our MONAI events. They provide a range of publicly available MONAI resources on the AWS platform. For a comprehensive list of these resources, please refer to the [AWS Resources README](https://github.com/Project-MONAI/monai-bootcamp/blob/main/aws_resources.md).
